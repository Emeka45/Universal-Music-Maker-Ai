# Universal Music Maker AI

Beautiful mobile-first AI music creator foundation. It includes prompt-to-song controls, genre chips, mood/length settings, vocals/instrumental options, a player surface, and local creation history.

## Generation architecture

The UI intentionally does not contain an API key. A secure server endpoint should receive the prompt and call a music-generation provider. Current providers can include Google's Lyria family or Stability AI's Stable Audio, subject to their current API access, licensing and pricing. Never commit provider keys to this public repository.

See the official current provider documentation before enabling production generation.