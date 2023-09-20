# lab06-debugging
Name: Xiaoxiao(Crystal) Zou & Ruijun(Danio) Zhong

[Our Shader](https://www.shadertoy.com/view/Dd3yzj)

Bugs:

<b>Line 97: vec->vec2</b>  Found this due to default complier error

<b>Line 100: uv->uv2</b> Found this due to wierd center point it is pointed at

<b>Line 75: eye->dir</b> Found this due to no reflection on metallic balls (or weird reflection)

<b>line 11: len * iResolution.x / iResolution.x->len * iResolution.x / iResolution.y </b>  Found this due to weird scaling of the screen objects

<b>line 18: 64->1000</b> Found this due to obersations of no intersections of the floor at further place.
# Setup 

Create a [Shadertoy account](https://www.shadertoy.com/). Either fork this shadertoy, or create a new shadertoy and copy the code from the [Debugging Puzzle](https://www.shadertoy.com/view/flGfRc).

Let's practice debugging! We have a broken shader. It should produce output that looks like this:
[Unbelievably beautiful shader](https://user-images.githubusercontent.com/1758825/200729570-8e10a37a-345d-4aff-8eff-6baf54a32a40.webm)

It don't do that. Correct THREE of the FIVE bugs that are messing up the output. You are STRONGLY ENCOURAGED to work with a partner and pair program to force you to talk about your debugging thought process out loud.

Extra credit if you can find all FIVE bugs.

# Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solution with the bugs corrected
- In the README, describe each bug you found and include a sentence about HOW you found it.
- Make sure all three of your shadertoys are set to UNLISTED or PUBLIC (so we can see them!)
