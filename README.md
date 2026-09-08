# Tale Weaver Studio

Clone this open source public GitHub repo and build project here fully working.
Make sure add all api keys secure never exposed them

https://github.com/godofgods414-hue/tale-tuner-studio.git

I made progress on both bugs before stopping:

Unfinished/incomplete pictures — panels were being accepted even when the image file was cut off mid-download; the checker now verifies each picture actually reaches its proper end before it's kept, otherwise the panel is drawn again. I also strengthened the art direction so every frame is asked to be fully finished and painted edge to edge.

One timestamp = one prompt — the prompt writer no longer throws away a whole batch of 120 prompts because a single line couldn't be written; each line now keeps its own slot, so prompts can never shift onto the wrong timestamp, and unwritten lines are left clearly empty for repair.

What still remains: the player page needs the matching change so an empty prompt is treated as "still missing" — kept in the repair loop and never sent to the picture generator — plus a final check that no timestamp is left without its own prompt before the video is built. I also haven't run a test pass on a long script to confirm the fixes end to end.
Pixazo api key 1
03178ba869a446eba82bce98a79fefc3

Pixazo api key 2
048e52aee2094e24bad1b46a0fb15753

Pixazo api key 3

d004a01679f843e7ba090fa1d88c926d

Pixazo api key 4
9379183b074f4655adc0fa351dd4fa29

Note for Open router:-
Open router has been 0 credits so make sure use only MiniMax: MiniMax M3 (free) model. I have given multiple open router api keys so make sure switch automatically when one daily quota reached.
All keys are working perfectly here https://minimax-m3-magic.lovable.app so don't use lovable fucking useless ai in any condition. Make sure add all keys properly.
Open router api key 1
@secret:OPENROUTER_API_KEY 

Open router api key 2
@secret:OPENROUTER_API_KEY 

Open router api key 3
@secret:OPENROUTER_API_KEY 

Open router api key 4
@secret:OPENROUTER_API_KEY 

Open router api key 5
@secret:OPENROUTER_API_KEY

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://narrative-art-weaver.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/4ae4c413-91ec-4d41-972e-e77ac41b7c84).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
