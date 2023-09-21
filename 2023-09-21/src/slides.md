---
layout: cover
highlighter: shiki
css: unocss
colorSchema: dark
transition: fade-out
growSize: 1.5
---

<div mt--2>
<h1 flex="~ col">
<div>The state of generative</div>
<div flex="~ gap3" items-center>Artificial Intelligence</div>
</h1>
<div tracking-wide op50>
~ Ismail Bahar
</div>
</div>

<div abs-bl mx-13 my-12 flex="~ col" text-sm text-left>
  <div>Funda Meetup</div>
  <div text-sm opacity-50>September 21st, 2023</div>
</div>

---
layout: intro
growX: 10
growY: 90
style: 'padding-left: 8rem;'
---

# Ismail Bahar

<div class="leading-10 opacity-80">
Team member of Agent Consumer Connect @ Funda.<br>
Enjoys experimenting with tech.
</div>

<div my-10 w-min flex="~ gap-1" items-center justify-center>
  <div i-ri-user-3-line op50 ma text-xl/>
  <div><a href="https://icba.dev" target="_blank" class="border-none! font-300">icba.dev</a></div>
  <div i-ri-github-line op50 ma text-xl ml4/>
  <div><a href="https://github.com/xyrai" target="_blank" class="border-none! font-300">xyrai</a></div>
  <div i-ri-twitter-line op50 ma text-xl ml4/>
  <div><a href="https://twitter.com/xyrai_" target="_blank" class="border-none! font-300">xyrai_</a></div>
</div>

<img src="https://avatars.githubusercontent.com/u/34368735?v=4" rounded-full w-35 abs-tr mt-32 mr-40/>

<div flex="~ gap2">

</div>

---
layout: quote
class: text-center
---

# My Experience

---
layout: center
growX: 50
growY: 120
growSize: 1.5
---

<h1 class="text-5xl!" w-200>Studying...</h1>
<h1 class="text-5xl!">Python</h1>
<h1 class="text-5xl!">Every. Single. Day.</h1>
<em class="opacity-50">for one year</em>
<img src="/timmy-turner-bored.gif" w-50 abs-tr mt-46 mr-40/>
---
layout: center
growX: -10
growY: 50
growSize: 0.75
---

<img src="/clerq.png" w-180 mix-blend-lighten filter-contrast-120 rounded-md />

---
layout: center
growX: -10
growY: 50
growSize: 0.75
---

<img src="/bp.png" w-200 mix-blend-lighten filter-contrast-120 rounded-md />

---
layout: center
growX: 50
growY: 0
growSize: 1.5
clicks: 4
---

<h1 class="text-5xl!" v-click="1" w-200>I <span transition-all duration-300 :class="$slidev.nav.clicks === 4 ? 'line-through op50' : ''">did</span> <span v-click="4">didn't</span></h1>
<h1 class="text-5xl! font-bold" v-click="2">Enjoy all</h1>
<h1 class="text-5xl!" v-click="3">of it.</h1>

---
layout: fact
growX: 0
growY: 50
---

<h1 class="text-4xl!">What happened?</h1>

---
layout: center
growX: -10
growY: -10
class: text-center
---

<img src="https://github.githubassets.com/images/modules/notifications/inbox-zero-dark.svg" />

<h4 mt-6 mb--4 font-bold>Enough!</h4>
<p op50 text-sm>
Take a break.
</p>


---
layout: fact
growX: 50
growY: 0
growSize: 1.5
---

# Artificial Intelligence
Bots with a brain 🤯

<div class="number-bg">0</div>

---
layout: center
growX: 50
growY: 100
growSize: 1.1
---

<div text-center mt4 op50 mb2>I participated in a bootcamp:</div>
<div flex="~ gap-2 items-center" text-3xl >
<div i-simple-icons-github/> <a href="https://github.com/Xyrai/Minor-AAI">Xyrai/Minor-AAI</a>
</div>
<div text-center mt4 op50 italic v-click>It's unorganized and in Dutch!</div>

---
growX: 110
growY: 110
---

<img absolute left-10 top-10 src="/models.png" w-150 />

<div absolute left-165 right-5 top-20>
<h4 font-semibold underline mb-4>The bootcamp in 4 steps</h4>
<v-clicks>

- Determine <b text-hex-a371f7>the problem</b>
  - Dataset
  - Labels
- Determine <b text-hex-a371f7>the classifier</b>
  - Hyperparameters
- Determine <b text-hex-a371f7>the method</b>
  - Preprocessing of data
  - Classifier comparison
  - Performance metric
- Evaluate <b text-hex-a371f7>the result</b>

</v-clicks>

<div v-click flex gap-4 items-center mt-6>
<div i-simple-icons-github /> <a href="/MLCheatSheet.pdf">Cheatsheet</a>
</div>
</div>

<!--
- Determine the problem
  - What is the problem?
  - What kind of labels do you have? Are they binary, numeric, long texts?
  - Do you have enough data? What is the dimension of the dataset?
  - What kind of data are you working with?

- Determine the classifier
  - What classifier will you use and why?
  - What are the important hyperparameters?
Example: The amount of clusters is an important factor when using K

- Determine the method
  - Are there any preprocessing steps you should take to prepare your data?
  - Are there other classifiers you can use and compare?
  - What is the best way to measure your prediction/result?

- Evaluate the result?
Which classifier delivered the best result, why so? Was your prediction correct?
-->

---
layout: fact
growX: -10
growY: -10
clicks: 1
---

<h2 font-semibold>StyleGAN</h2>
<span italic opacity-50>The magical image generator</span>

<img src="/stylegan.webp" :class="$slidev.nav.clicks === 0 ? 'op100!' : 'hidden op0'" mt-4 h-100 mx-auto />

<div mt-4 flex :class="$slidev.nav.clicks === 1 ? 'op100!' : 'op0'">
  <img src="/pokemon.gif" w-100 h-100 mx-auto />
  <img src="/cat.gif" w-100 h-100 mx-auto />
</div>

<!--
Generative Adversarial Networks (GAN)
-->

---
layout: fact
growX: -10
growY: -10
---

<h2 font-semibold>StyleGAN2 & FOMM</h2>
<span italic opacity-50>Another magical image generator combined with an animator</span>

<div flex>
  <video src="/relative.mp4" w-100 h-100 mx-auto autoplay muted loop />
  <video src="/absolute.mp4" w-100 h-100 mx-auto autoplay muted loop />
</div>

<div op50 flex justify-between class="mx-4">
  <span>Relative</span>
  <span>Absolute</span>
</div>

<!--
First Order Motion Model (FOMM)
-->

---
growX: -10
growY: -10
class: text-center
---

<h2 font-semibold>Tacotron</h2>
<span italic opacity-50>A speech synthesis model</span>

<div mt-4 flex gap4>
  <img src="/tts.png" w-110 h-full mx-auto />
  <img src="/sts.png" w-110 h-full mx-auto />
</div>

---
layout: center
growX: -10
growY: -100
---

<div flex>
  <video src="/voices.mp4" mx-auto controls />
</div>
---
layout: fact
growX: 50
growY: 0
growSize: 1.5
---

# Diffusion Models
The Golden Era of A.I.

<div class="number-bg">1</div>

---
growX: -10
growY: -10
class: text-center
clicks: 1
---

<h2 font-semibold>What is a diffusion model?</h2>

<div mt-8 flex justify-center items-center gap4>
  <img src="/diffusion.png" v-click="0" :class="$slidev.nav.clicks === 0 ? 'op100' : 'op0 hidden'" w-full h-full mx-auto />
  <img src="/diffusion.gif" v-click="1" :class="$slidev.nav.clicks === 1 ? 'op100' : 'op0 hidden'" w-full h-full mx-auto />
</div>

---
layout: fact
growX: 0
growY: 50
---

<h1 class="text-4xl!">Stable Diffusion</h1>

---
layout: center
---

<h1>Basic Setup</h1>
<v-clicks depth="2">

<div flex items-center gap2 mb4> <div i-simple-icons-github /> <a href="https://github.com/lllyasviel/Fooocus/" target="_blank">Fooocus by lllyasviel</a></div>

Make sure to have the required dependencies installed (see: [environment.yaml](https://github.com/lllyasviel/Fooocus/blob/main/environment.yaml))

<div>
<h4 font-semibold mt8 mb1>What is Foooocus?</h4>
An improved user experience on top of Stable Diffusion XL inspired by Midjourney
</div>

</v-clicks>

<!--
If you get an error while installing the requirements, make sure to upgrade your pip version to the latest one.
Command: python3 -m pip install --upgrade pip
-->

---
growX: -10
growY: -100
---


<h2 text-center>Album Covers</h2>
<div grid grid-cols-3 gap4 items-center justify-center h-full>
<div flex flex-col items-center>
  <img src="/four.png">
  <span op50></span>
</div>

<div flex flex-col items-center>
  <img src="/five.png">
  <span op50></span>
</div>

<div flex flex-col items-center>
  <img src="/six.png">
  <span op50></span>
</div>

<div flex flex-col items-center>
  <img src="/seven.png">
  <span op50></span>
</div>

<div flex flex-col items-center>
  <img src="/eight.png">
  <span op50></span>
</div>

<div flex flex-col items-center>
  <img src="/nine.png">
  <span op50></span>
</div>
</div>

<!--
Prompts used:

an album cover in winter at night with cozy hoodies female from the back
an album cover in winter at night with cozy hoodies female and stars
an album cover in winter at night with cozy hoodies male and stars
an album cover in winter at night with cozy hoodies
-->

---
growX: -10
growY: -100
---
<h2 text-center>Fantasy / Anime</h2>

<div grid grid-cols-3 gap4 items-center justify-center h-full>
<div flex flex-col items-center>
  <img src="/one.png">
  <span op50></span>
</div>

<div flex flex-col items-center>
  <img src="/two.png">
  <span op50></span>
</div>

<div flex flex-col items-center>
  <img src="/three.png">
  <span op50></span>
</div>
</div>

---
growX: -10
growY: -100
---
<h2 text-center>Twitch Emotes (Stickers)</h2>

<div grid grid-cols-4 gap4 items-center justify-center h-full>
<div flex flex-col items-center>
  <img src="/twitch1.png" class="rounded-lg">
</div>

<div flex flex-col items-center>
  <img src="/twitch2.png" class="rounded-lg">
</div>

<div flex flex-col items-center>
  <img src="/twitch3.png" class="rounded-lg">
</div>
<div flex flex-col items-center>
  <img src="/twitch4.png" class="rounded-lg">
</div>
</div>

---
growX: -10
growY: -100
---

<h2 text-center>Architecture</h2>

<div grid grid-cols-3 gap4 items-center justify-center h-full>
  <img src="/house1.png">
  <img src="/house2.png">
  <img src="/house3.png">
</div>

---
layout: fact
growX: 0
growY: 50
---

<h1 class="text-4xl!">Demo</h1>

---
layout: center
---

<h1>Must Knows 🍀</h1>

<v-clicks depth="2">
<div>
  1. Checkpoints <br>
  <span op50>Checkpoint of the model you will be using.</span>
</div>

<div mt3>
  2. Low-Rank Adaptation (LoRA) <br>
  <span op50>Fine-tuning diffusion models, these are used to make small styling adjustments.</span><br>
  <span op50 text-sm>I call them "tiny models" 🤫</span>
</div>

<div mt3>
  3. Prompts <br>
  <span op50>Positive: What do you want to generate?</span><br>
  <span op50>Negative: What do you NOT want to generate?</span>
</div>

  ```json
    {
      "name": "Default (Slightly Cinematic)",
      "prompt": "cinematic still {prompt} . emotional, harmonious, vignette,
        highly detailed, high budget, bokeh, cinemascope, moody, epic, gorgeous, film grain, grainy",
      "negative_prompt": "anime, cartoon, graphic, text, painting, crayon,
        graphite, abstract, glitch, deformed, mutated, ugly, disfigured"
    }
  ```

<div mt3>
  4. Weights <br>
  <span op50>The importance of a certain criteria.</span>
</div>
</v-clicks>

---
layout: center
growX: -10
growY: -100
---

# Want to use another model?

Make sure to visit [CivitAI](https://civitai.com/models) or create your own.

<img src="/civitai.png">


---
layout: center
---

<h1>Advanced Setup</h1>
<v-clicks depth="2">

<div flex items-center gap2 mb4> <div i-simple-icons-github /> <a href="https://github.com/AUTOMATIC1111/stable-diffusion-webui" target="_blank">Stable Diffusion Web UI by AUTOMATIC1111 </a></div>

Make sure to have the required dependencies installed (see: [environment-wsl2.yaml](https://github.com/AUTOMATIC1111/stable-diffusion-webui/blob/master/environment-wsl2.yaml))

<div>
Use the following command if running webui-user.bat does not work:
```python
 pip install -r requirements.txt 
```
</div>

<div>
<h4 font-semibold mt8 mb1>What is Stable Diffusion Web UI?</h4>
A web interface built for Stable Diffusion models with a lot of settings.
</div>

</v-clicks>

---
growX: -10
growY: -100
---

<h2 text-center>Instagram Model</h2>

<div grid grid-cols-3 items-center justify-center h-full gap4 >
  <img src="/model1.png">
  <img src="/model2.png">
  <img src="/model3.png">
</div>

---
growX: -10
growY: -100
---

<h2 text-center>Inpainting</h2>

<div flex items-center justify-center h-full gap4 >
  <img src="/avatar1.png" class="h-7/8">
  <Arrow x1="200" y1="200" x2="430" y2="325" text-red-700  />
  <img src="/avatar2.png" class="h-7/8">
</div>

---
layout: fact
growX: 0
growY: 50
---

<h1 class="text-4xl!">Demo</h1>

---
growX: -10
growY: -100
layout: center
---

<h2 text-center>Videos with Deforum</h2>

<div flex items-center justify-center>
  <video src="/dance1.mp4" controls mt2 />
</div>

---
growX: -10
growY: -100
layout: center
---


<div grid grid-cols-3 items-center justify-center gap-4>
  <div flex flex-col>
    <video src="/dance2.mp4" autoplay muted loop />
    <span>without ControlNet</span>
  </div>
    <video src="/dance1.mp4" autoplay muted loop />
    <div flex flex-col>
    <video src="/dance3.mp4" autoplay muted loop />
    <span>with ControlNet</span>
  </div>
</div>

---
layout: center
---

# ControlNet
A neural network to control diffusion models

**Installation Guide:**
<v-clicks depth="2">

- Open the **Extensions** tab in Stable Diffusion Web UI
  - Open the **Available** tab
  - Press the **Load from** button
  - Install `sd-webui-controlnet`
- [Install ControlNet Models](https://huggingface.co/lllyasviel/ControlNet-v1-1/tree/main)
  - Great ones are: depth, canny, openpose, lineart_anime
- Place the installed models in your folder ControlNet extension folder
  - Path: `WebUI -> extensions -> sd-webui-controlnet -> models`
  - If this doesn't work, then place them in: `WebUI -> models -> ControlNet`
</v-clicks>

---
growX: -10
growY: -100
layout: center
---

<h2 text-center>Tears for Fears - Everybody Wants To Rule The World</h2>

<div flex items-center justify-center>
  <video src="/trailer.mp4" controls mt2 />
</div>

---
growX: -10
growY: -100
---

<h2 text-center>Tears for Fears - Everybody Wants To Rule The World</h2>

<div grid grid-cols-2 gap4 items-center justify-center mt20>
  <video src="/original-video.mp4" controls autoplay muted loop />
  <video src="/anime-video.mp4" controls autoplay muted loop />
</div>

---
layout: center
growX: -10
growY: -100
---

# Want "better" videos?
Have a look at the following methods and projects:

- [The TokyoJab Grid Method](https://www.reddit.com/r/StableDiffusion/comments/11z2emv/comment/jdb2lfu)
- TemporalKit + TemporalNet
- [Runway ML](https://runwayml.com/)

<video src="/tokyojab.mp4" autoplay muted loop w-50 abs-tr mt-46 mr-15/>

---
layout: center
---

<h2 text-center>Real World Applications</h2>

- [Linkin Park - Lost (Music Video)](https://www.youtube.com/watch?v=7NK_JOkuSVY)

- [Lumi_N0va (A.I. Virtual Character)](https://www.youtube.com/watch?v=YEf4unw1DvE)

- [Interior AI](https://interiorai.com/)
- and many more..

---
layout: center
---

<h2>Want to learn more on your own?</h2>
<span op50> Here are some YouTube channels I can highly recommend:</span>

- [Sebastian Kamph](https://www.youtube.com/@sebastiankamph)
- [Albert Bozesan](https://www.youtube.com/@albertbozesan)
- [bycloud](https://www.youtube.com/@bycloudAI)
- [Jarods Journey](https://www.youtube.com/@Jarods_Journey)

---
layout: center
---

<div w-100>

<h1 mb-2>Key Takeaways</h1>

<v-clicks>

- Study Python 🐍
- Create bots 🤖
- Create even more bots 🤖🤖
- Get tired of creating bots 😴
- Dive into creating bots with a 🧠
- Have fun!
</v-clicks>

</div>

---
layout: center
growX: 50
growY: 0
---

# Thank You!

Slides are on [icba.dev](https://icba.dev) and [GitHub](https://github.com/xyrai/talks)
