# 🎬 Module 2: Digital Art & Video Generation (Visual Storytelling)

Learn to use AI to generate images and stitch them together into a dynamic video narrative using **Google Flow**.

---

## 🎯 Learning Objectives

By the end of this module, you will be able to:
- [ ] Write detailed, descriptive prompts to generate specific images
- [ ] Use Google Flow to create animated videos from still images
- [ ] Extend AI-generated video clips to build a continuous narrative
- [ ] Understand the difference between generating individual assets and crafting a cohesive story

---

## 💼 Why This Matters

| Career | How They Use This Skill |
|--------|------------------------|
| **Video Editor / Producer** | Storyboarding and creating pre-visualization animatics |
| **Marketing Professional** | Producing rapid promotional video content for social media |
| **Concept Artist** | Bringing static concept art to life quickly |
| **Content Creator** | Generating engaging visual b-roll and backgrounds |

> **⚠️ Note on "AI Slop" and Traditional Tools:** 
> While the video we create in this module showcases the incredible technical power of AI to generate motion from text, the resulting narrative might feel a bit chaotic or disjointed—sometimes referred to colloquially as "AI slop." The AI is excellent at generating visuals, but it lacks an inherent understanding of traditional storytelling, pacing, or physical logic. It's up to *you* as the director to try to guide it! 
> 
> *Historically, creating these kinds of dynamic, realistic animations required years of training and complex software like **Adobe After Effects, Autodesk Maya, Premiere Pro, or Blender**. Now, AI allows us to prototype these ideas rapidly using just natural language compared to the technical prowess needed in the past.*

---

## 🔑 Key Concepts

### What is Visual Storytelling with AI?

Instead of relying on a single static image, we are using AI to generate multiple keyframes and blending them into a moving sequence.

| Component | Description |
|-----------|-------------|
| **Base Images** | The starting point for your video. Establishing shots and key characters. |
| **Motion Prompts** | Text descriptions telling the AI exactly *how* things should move. |
| **Extension** | Adding new scenes onto the end of an existing video clip to build a longer story. |

---

## 🛠️ Tools for Today

| Tool | What It Does | Access |
|------|--------------|--------|
| **Google Flow** | Creates short animated videos from images and text prompts | [labs.google/fx/tools/flow](https://labs.google/fx/tools/flow) |
| **Google Gemini** | Generate images and get creative ideas | [gemini.google.com](https://gemini.google.com) |

> **⚠️ Note:** Google Flow requires a **regular Google account** (not a child/supervised account). For this workshop, we've set up a specific Flow project using the Nano Banana Pro engine to create images and videos.

---

## 📷 Before You Start

Prepare your materials. You can follow the manual steps outlined in the activities below to recreate the project yourself.

---

## 🎬 Activity A: Visual Storytelling with Flow

In this activity, we will create a wild, surreal story about a cat and a gorilla at the zoo by stitching together a video narrative!

### Step 1: Generating the Base Images

First, we need to generate our core assets. In Google Flow (or another image generator like Gemini), try using these detailed prompts to generate the static images we will use as keyframes.

1. "A documentary-style, hyper-realistic photo taken inside a spacious, rocky zoo enclosure on a bright, slightly overcast day. The setting features simulated rock formations, thick green foliage in the background, and scattered dry grasses on the ground. A massive, adult silverback gorilla, with coarse grey and black fur, sits atop a large, flat rock in the middle-right, looking down with a curious, puzzled expression. In the foreground-left, sitting vulnerably in the grass and looking very small, is a domestic orange tabby cat, its eyes wide with alarm. Dust motes float in the air. The photo is taken at ground level with a shallow depth of field, rendering the zoo viewing glass and blurred human spectators in the far background. The lighting is natural but dramatic."  
![alt text](1-gorilla-and-cat.png)

2. "A close-up photograph of an orange tabby cat's front paws gripping the rusted metal edge of an elevated zoo observation deck. Looking straight down past the cat's paws, a vast, rocky gorilla enclosure is visible far below, bathed in bright daylight. A massive silverback gorilla sits on a central rock in the distance."  
![alt text](2-cat-at-edge.png)

3. "A medium shot of diverse human spectators standing on an elevated zoo observation deck, looking over a rusted metal railing. They are looking down with calm, curious expressions. Bright daytime lighting. The background is clear blue sky and distant trees."  
![alt text](3-spectators.png)

4. "A high-angle telephoto shot from above. A massive silverback gorilla sits on a large flat rock in a zoo enclosure. It is looking directly up and over its shoulder with a squinting, surprised expression. Bright daylight highlights the gorilla's face against the blurred upper railing of an observation deck in the background."  
![alt text](4-gorilla-lookup.png)

5. "A dynamic, wide-angle ground-level photograph looking sharply up from a rocky zoo enclosure floor. An orange tabby cat is captured mid-air, dynamic and fully stretched, leaping downward. In the background, slightly blurred, a silverback gorilla looks up in shock. Bright daylight, dramatic shadows."  
![alt text](5-cat-jump-into-gorilla.png)

6. "A hyper-realistic photo in a bright, rocky zoo enclosure. A massive silverback gorilla is standing upright, beating its chest aggressively. Facing it is a magnificent adult male African lion with a dark mane, lunging forward with claws extended, roaring violently. Dust kicks up around their feet in the bright daylight."  
![alt text](6-gorilla-and-lion.png)

7. "A medium shot of diverse human spectators standing on an elevated zoo observation deck, looking over a rusted metal railing. Their faces show pure shock and terror, with gasps and pointing fingers. Bright daytime lighting. Below them is a blurred rocky gorilla enclosure."  
![alt text](7-terrified-spectators.png)

8. "A wide-angle cinematic photo inside a rocky zoo enclosure. Deep twilight shadows contrast with saturated theatrical stage lighting (purples, reds, golds) and heavy smoke. A silverback gorilla sits behind a massive chrome double-bass drum kit, wildly striking cymbals. A large male lion stands upright on its hind legs, shredding a cherry-sunburst Gibson Les Paul electric guitar. Surreal, hyper-realistic."  
![alt text](8-lion-gorilla-rock-band.png)

9. "A medium shot of diverse human spectators standing on an elevated zoo observation deck, looking over a rusted metal railing. Their faces show pure shock and terror, with gasps and pointing fingers. Bright daytime lighting. Below them is a blurred rocky gorilla enclosure." *(Note: This visually mirrors image #7!)*  
![alt text](9-people-in-rock-concert.png)


### Step 2: Creating the Initial Video Clip

At the time of creating this video in Flow, you can choose up to **3 base images** to guide the initial generation. 

1. Select our setup images representing the tension at the zoo (`2-cat-at-edge.png`, `3-spectators.png`, and `5-cat-jump-into-gorilla.png`).
2. Enter the following multi-scene prompt to direct the motion:

> "Cinematic close-up video. An orange tabby cat is perched on the rusted metal railing of an elevated zoo observation deck. The camera slowly pushes in on the cat's face as it intensely stares down into the blurred rocky enclosure below. Bright natural daylight, highly detailed.
> Medium shot video. A diverse group of human spectators stand at a zoo observation deck railing on a sunny day. They are casually looking down, pointing, and smiling gently. The camera slowly pans across their faces.
> Action camera video from a low angle. An orange tabby cat suddenly leaps off the high metal railing of the observation deck, diving straight down toward the camera. The cat is mid-air, fully stretched out against the bright sky."

![alt text](video-prompt.png) 

<a href="https://www.youtube.com/watch?v=YXigSs8oPvI" target="_blank"><img src="https://img.youtube.com/vi/YXigSs8oPvI/0.jpg" alt="Cat leaps off"></a>

### Step 3: Extending the Narrative (Part 1)

Now that we have our core starting clip, we use Flow's **">> Extend"** option to add more runtime to our video based on our continuation of the story.

Use this prompt to extend the video:

> "Telephoto video shot. A massive silverback gorilla sitting on a rock abruptly flinches backward, tilting its head sharply upward to look at the sky with wide-eyed surprise. Dust gently swirls around its feet in the bright daylight.
> Cinematic video at ground level. The orange cat lands on the rocky ground in front of the gorilla. Upon impact, there is an immediat    e, blinding burst of golden magical light and thick smoke. As the smoke rapidly clears within a second, a massive male lion with a dark mane stands in the cat's place, letting out a furious roar.
> Fast-paced medium video shot. The human spectators on the observation deck suddenly recoil in absolute terror. They gasp, point downwards with shaking hands, and cover their mouths in pure shock. Bright daylight."

<a href="https://www.youtube.com/watch?v=7HCatchJQso" target="_blank"><img src="https://img.youtube.com/vi/7HCatchJQso/0.jpg" alt="Cat turns into lion"></a>

### Step 4: The Grand Finale (Extending Part 2)

Let's extend the video one more time to give our story a surreal, unexpected, logic-defying ending!

Use this prompt to finish the sequence:

> "Intense action video, handheld camera style. The silverback gorilla and the massive male lion charge at each other in the rocky daytime enclosure. They collide, grappling and roaring aggressively, kicking up a massive cloud of dirt and dust.
> A rapid, stylized transition video. As the lion and gorilla grapple in the dust, the bright daytime lighting suddenly drops to deep twilight. Instantly, flashing theatrical rock concert spotlights (deep purples, reds, golds) burst on from the surrounding rocks, cutting through the thick dust which now looks like concert stage smoke.
> Surreal cinematic video. In a rocky enclosure lit by flashing purple and red stage lights and heavy smoke, a large male lion is standing upright on its hind legs, enthusiastically shredding a cherry-sunburst electric guitar. Next to him, a massive silverback gorilla is wildly smashing a full drum kit with drumsticks. They are headbanging to the music.
> Slow-motion cinematic video. The human spectators on the observation deck are now bathed in flashing red and purple concert lights and atmospheric haze. Their terror has vanished; instead, they are grinning wildly, throwing their hands in the air, and aggressively headbanging to the heavy rock music."

<a href="https://www.youtube.com/watch?v=NLTjkDGdHcE" target="_blank"><img src="https://img.youtube.com/vi/NLTjkDGdHcE/0.jpg" alt="Lion and Gorilla Concert"></a>
---

## 🔄 Activity B: The Narrative Remix Challenge

The key to AI video generation isn't getting it right the first time—it's **iteration** and exploring alternatives. The story above is just one path! 

What if the cat *didn't* turn into a lion? What if it turned into a giant golden eagle? What if the spectators jumped down to help? What if they all played jazz instead of a heavy rock concert? 

**The Challenge:**
Create a unique twist to the narrative:

1. **Version 1:** Start with the exact same three base images we did in Activity A Step 2. Generate a new initial video.
2. **Version 2:** Radically change the **Step 3 and Step 4** extension prompts. 
3. Take the story in an absolutely different direction! Compare how the mood and the "slop" factor changed.

### Reflection Questions

- Which version do you like best? Why?
- What surprised you about how AI interpreted your motion and story inputs?
- Was it hard to keep the AI from hallucinating or losing track of characters between extensions?
---

## 🕵️ Activity C: Reverse-Engineering a Viral Short

Now that you know how to build a video from scratch, let's look at a popular video and try to work backwards! By analyzing successful content, we can learn how to write better prompts.

**The Challenge:**
1. Watch this hilarious viral YouTube Short: 

<a href="https://www.youtube.com/watch?v=2nZ59mEKiOQ" target="_blank"><img src="https://img.youtube.com/vi/2nZ59mEKiOQ/0.jpg" alt="Black Poodle"></a>

2. **Analyze the Scene:**
   - What are the main **characters**? (An orange tabby cat, a fuzzy black poodle, and another poodle watching in the background).
   - What is the **setting**? (An outdoor patio with a gray brick wall, a bamboo-style shelf, and a large stainless steel bowl).
   - What is the **action**? (The cat "lights" a firecracker, and then the cat and black poodle sit side-by-side with their mouths wide open as if laughing).
3. **Write the Base Prompt:** Try to write the most descriptive prompt possible to generate a starting image that looks exactly like the outdoor patio with the cat, the poodles, and the firecracker.
4. **Animate the Action:** Use Flow to animate the pets' vocal "laughing" reaction to the firecracker. Try to get the AI to make them sit side-by-side with open mouths!

*Hint: AI struggles with rapid, specific logical movements (like a cat lighting a tiny fuse with its paw). You might need to focus on the broad action and the funny reactions rather than perfect realism!*

---

## 🖼️ Gallery Walk (If in a group)

1. Wait for everyone to finish their remixed videos.
2. Select your craziest, most surreal narrative video.
3. Display it on your screen.
4. Walk around and view 3-4 classmates' work.
5. For each piece, note:
   - One thing you like about their creative direction
   - A question you have (e.g., how did they achieve that transition effect?)

---

## 📝 Reflection Journal

```
MODULE 2: THE VIDEO NARRATIVE ERA

TOOLS I USED TODAY:
[ ] Google Flow
[ ] Google Gemini
[ ] Other: _______________

MY BEST CREATION:
Core Character: _______________________
Action/Plot Twist: _________________________
What I like about it: ___________

ITERATION DISCOVERY:
The biggest change happened when I adjusted my prompt to say: _______________
I learned that the AI responds well to: _______________________

STORYTELLING VOCABULARY I LEARNED:
1. _______________
2. _______________
3. _______________

NEXT TIME I WOULD TRY:
_____________________________________________
```

---

## 📚 Key Vocabulary

| Term | Definition |
|------|------------|
| **AI Slop** | Artistically chaotic or narratively disjointed content generated rapidly by AI. |
| **Iteration** | Making repeated attempts, adjusting prompts and styles each time based on results. |
| **Subject / Base Image** | The main focus or initial visual keyframe in an establishing shot. |
| **Motion Prompt** | Instructions that describe exactly how elements should move in an animation. |
| **Extension** | Further generating consecutive scenes off the tail end of an existing AI video clip. |

---

## ✅ Skills Checklist

By the end of this module, you should be able to:

- [ ] Explain how AI video narrative extensions work
- [ ] Use Flow to combine base images with motion prompts
- [ ] Iterate on AI outputs to improve scene transitions
- [ ] Use descriptive vocabulary to guide AI camera angles and actions
- [ ] Reverse-engineer existing videos to understand their prompt structure
- [ ] Understand the limitations of narrative consistency with current generative models

---

## 🚀 Extension Activities

### Action Movie Sequence Challenge
Combine totally unrelated chaotic ideas into an action sequence:
- "A high speed car chase transitioning into an underwater submarine battle."
- "A quiet library dramatically erupting into a zero-gravity laser tag arena."

### Music Video Creator
Using a song you love as inspiration, create an AI visualizer:
1. Choose a song and identify its core tempo/mood.
2. Generate base images that represent the music's vibe.
3. Iteratively extend a Flow video that builds visually to match the drop or chorus of the song!

---

## 🏠 Take-Home Challenge

**Create Your Digital Storyboard:**

1. Come up with a 3-scene story you want to create (Beginning, Middle Twist, and End).
2. Write 2-3 sentences max for the motion prompts of each scene.
3. Generate the 3 *Base Images* using Google Gemini or another image generator that best establish the setting and mood.
4. Bring these to the next module so we can use them as assets for our next coding projects!

---

[⬅️ Back to Main Guide](../../README.md) | [Next Module: Coding with Your Voice ➡️](../03-vibe-coding/README.md)
