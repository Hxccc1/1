---
license: cc0-1.0
---
# This repo is.
This repository shares various Merge models that can be used with StableDiffusionWebui:Automatic1111 and others.

## Reference
+/hdg/ Stable Diffusion Models Cookbook - https://rentry.org/hdgrecipes#g-anons-unnamed-mix-e93c3bf7

# Merge Recipes

### ElderOrangeMix [3a46a1e0] ｜anything and everything mix ver.1.5+Gape+Nai(AnEve.G.N0.3)

▼Use Models
1. anything and everything mix ver.1.5 [5265dcf6]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

### **Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.5 | anything and everything mix ver.1.5 | Gape60 | NovelAI full | tempmix-part1 [] |
| 2 | Add Difference @ 0.3 | tempmix-part1 | NovelAI full | NovelAI sfw | ElderOrangeMix  [3a46a1e0] |

----

### BloodOrangeMix [ffa7b160]｜Anything+Nai+Gape

▼Use Models
1. AnythingV3.0 huggingface pruned [2700c435]
2. NovelAI animefull-final-pruned [925997e9]
3. NovelAI sfw [1d4a34af]
4. Gape60 [25396b85]

### **Instructions:**

| Step | Interpolation Method | Primary Model | Secondary Model | Tertiary Model | Merge Name |
| --- | --- | --- | --- | --- | --- |
| 1 | Add Difference @ 0.3 | AnythingV3.0 | NovelAI animefull | NovelAI sfw  | tempmix-part1 [] |
| 2 | Add Difference @ 1.0 | tempmix-part1 | Gape60 | NovelAI animefull | BloodOrangeMix [ffa7b160] |