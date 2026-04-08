# Comment Intent Mapping

Map user intent to fast generation presets for Myspace-style comment assets.

## Intent classes
- `supportive_reply`: warm friend response, gratitude, encouragement.
- `event_shoutout`: birthdays, congrats, milestone hype.
- `flirty_ping`: playful affection and attention-seeking.
- `light_drama`: indirect callout energy without explicit harassment.
- `nostalgic_signoff`: guestbook-style return-message etiquette.

## Recommended generation knobs
- **text_length**: 2–7 words
- **effect_intensity**: medium_high to high
- **artifact_level**: medium (raise for authenticity)
- **animation_speed**: fast for drama, medium for supportive
- **clutter_density**: medium_high (comment graphics should still read quickly)

## Routing logic
1. Detect intent from message text and punctuation.
2. Pick one base template from `10_prompt_system/comment_graphic_prompt_templates.md`.
3. Inject era shorthand and emotional keyword.
4. Apply palette preset based on intent:
   - supportive_reply -> `bubblegum_shock`
   - event_shoutout -> `barbie_reactor`
   - flirty_ping -> `kiss_badge_pop`
   - light_drama -> `goth_glow_gel`
   - nostalgic_signoff -> `nightclub_nebula`
5. Run anti-drift checks before final output.

## Safety and policy note
For `light_drama`, avoid slurs, threats, or direct harassment. Keep tone performative and stylized.
