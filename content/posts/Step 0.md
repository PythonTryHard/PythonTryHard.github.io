+++
title = "Step 0 - Setting your expectations"
date = "2023-03-10T02:44:27+07:00"
author = "PythonTryHard"
authorTwitter = "" #do not include @
cover = ""
tags = []
keywords = [] 
description = "Before we beginning, I have some things to tell you."
showFullContent = false
hideComments = false
color = "" #color from the theme settings
+++
## 1. Programming doesn't need a degree

So, who am I? What am I in the world to be telling you what to do? What qualifications do I have to tell you what is good, and what is bad? Simple answer: **I am a nobody. No programming qualifications, no computer degrees, no nothing. I am just some stranger on the Internet to you, writing a "course" as a way to give back to the community that has helped me so much along the way, enabling me to write this to you with a certain level of confidence**.

"So you're telling me, that I'm about to learn how to write code, from someone that doesn't write code professionally?" - I hear you ask.

And the answer is "Yes". Yes you are. My bread winner is food engineering, not software engineering. But, being part of the engineering space, and having fought through the muck of programming myself on my own, I can say this:

> The difference between an engineer and a field's casual, is being able to deal with problems at scale.

Using an analogy I love to use in my field: Anyone can make tomato sauce, but a food engineer can make tomato sauce **at scale**. To make tomato sauce, you only need a pan, a stove, tomatoes, spices, some kitchen tools, and that's it. But at scale, you want machines to handle that for you. And to devise a plan for what machines to use, in which order, pre-processing, post-processing, all of that needs an engineering degree to ensure any bottle of tomato sauce is the same as millions of other bottles of tomato sauce.

The same can be said about programming. Anyone can write code, but a software engineer can write code **at scale**. You can write code to make a Discord bot, but a software engineer can write code to make a Discord bot that can operate in tens of thousands of Discord servers. Because only at scale does every single tiny details matter.

## 2. I'm not teaching you to be a software engineer, but I will teach you what a software engineer do regularly

You're here to write code. You're here to learn how to cook tomato sauce on a pan at home. You're not gonna be solving the problems-at-scale anytime soon. **But**, and here's the big but: You will learn to do things the way the Python community has been doing, and only then are you allowed to do things your way. By having a baseline of what is correct, you can then choose to deviate from that baseline, knowing you have stable ground to head back should something goes wrong. It's the same reason why we don't give children calculators in grade school until they have proven proficiency in basic maths.

## 3. Prepare to be disillusioned, this is not a theme park

The misconception of "Programming is magic! Magic in, magic out!" has been on the rise for quite a while, especially with the rise of one-click apps, of YouTube tutorials covering the "cool kids' stuffs" targetting the wide general public. ChatGPT making "writing code" trivial, Python being the language of A.I.. People rushing in to Python hoping to create their own piece of tech, to have their hands on what used to be the unknowns.

But human's needs is endless, unsatisfiable. Translating a proverb from my native tongue: From eating full and dressing warm, to eating nice and dressing good. We always strive for more. Back to tomato sauce again: You now have a pan of tomato sauce. Why not add garlic to it? Just mince out some garlic and throw in! And lo-and-behold: It tastes like suck: The garlic is chunky against a mushy tomato base. You didn't burn the garlic too, right?

Same goes for programming. Unarmed, you take the code for a Discord bot from a tutorial and try to add a small new feature. Uh oh. Code errors out. Okay, let's do it differently. Nope, still errors. Maybe this will do...? Nuh-uh. Panic, confused, you start to look for a place to get help. And you ask:

>*You*: Guys help my Discord bot not working

People start to come in. Because you didn't tell them anything, they will start asking

>*Them*: Well, where's your code?

You give them your code. It looks messy, but you're sure because they're better than you, they will surely find the problem. They found it. They tell you how to fix it. You fix it, proudly, asking them whether your fix is correct.

>*Them*: No not like that, you're supposed to...

>*You*: Huh? So, like this?....

>*Them*: Not like that, like this!

I have seen this conversation many times. I have been at both ends of this conversation many times. What's the problem here? It's not your fault, absolutely: You don't know how to do, it's natural to make mistakes. The problem here, is **you are trying to run before you can walk**. Python is a loaded toolbox, but without knowing how to use the tools, you will absolutely whack yourself in the head. A painful lesson, and you never pick up programming again. It's scary. It's too hard. It's not for me.

That's why, before we begin, you must remember to forget **EVERYTHING MAGICAL** you think programming is, and prepare to slam yourself into brick walls after brick walls, each brick wall being more brick wall than the last. Only then are you able to start programming the same way as everyone else, with your first neatly-written, bug-free, perfect program:

```python
class TestForeignScreenshots:
    """Test the parsing of screenshots generated by other players."""

    def test_fixed_calibration(self, file_name, gear_object):
        """Test auto calibration for foreign screenshots"""
        image = cv2.imread(file_name)
        scaling_factor = calibrate_scale(image, rounds=2, sweep_steps=40)
        parser_result = parse_screenshot(rescale(image, *calculate_rescaled_size(image, scaling_factor)))
        assert parser_result == gear_object

    def test_dynamic_calibration(self, file_name, gear_object):
        """Test auto calibration for foreign screenshots"""
        image = cv2.imread(file_name)
        scaling_factor = calibrate_scale(image, rounds=2, sweep_steps=[50, 20])
        parser_result = parse_screenshot(rescale(image, *calculate_rescaled_size(image, scaling_factor)))
        assert parser_result == gear_object
```

And bring your tomato sauce along. You will be seeing tomato sauce a lot along the way.