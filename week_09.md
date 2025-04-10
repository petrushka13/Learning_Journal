# Learning Journal Week 09

## CSS Pre-processing with Sass

**Weekly Objectives:**

- [x] Create small website using Sass
- [x] Group project: finalise decisions regarding layout, css/sass, content, planning, workflow (if able)

### Learning Activity

Sass <br>
[Sass Essential Training 2015](https://www.linkedin.com/learning/sass-essential-training/welcome?u=2223545) <br>
[Sass In 100 seconds](https://www.youtube.com/watch?v=akDIJa0AP5c)<br>
[Sass Tutorial for Beginners - CSS With Superpowers](https://www.youtube.com/watch?v=_a5j7KoflTs)<br>
[Stop using an extension to compile Sass](https://www.youtube.com/watch?v=o4cECvhrBo8) <br>
[Sass / SCSS COMPLETE Tutorial (+ Node.js & NPM) with Real-World Example](https://www.youtube.com/watch?v=ztEY-uber4U) <br>
[What is NPM, and why do we need it? | Tutorial for beginners](https://www.youtube.com/watch?v=P3aKRdUyr0s) <br>
[Browsersync + Sass + Gulp in 15 minutes](https://www.youtube.com/watch?v=q0E1hbcj-NI) <br>
[Sass @import is being replaced with @use and @forward](https://www.youtube.com/watch?v=dOnYNEXv9BM) <br>
Estimated Time: 6h 30m

#### Content Insights:

As a beginner, I found the LinkedIn Sass training video a bit too advanced right from the start. To better understand how Sass is set up, I turned to other tutorial videos. Most of them used Sass compiler extensions, which wasn't what I was trying to learn. One video titled *"Stop Using an Extension to Compile Sass"* helped clarify why relying on extensions isn't ideal—mainly due to issues with robustness and keeping things up to date. However, that video didn’t cover the Gulp-based approach like the LinkedIn course did. 

What really helped was a video focused on NPM, which finally made things clearer for me. It introduced useful commands like `node -v` and `npm -v` to check installed versions. This was especially helpful because I had different Node.js versions—one being used by PHPStorm and another globally in my command line—and I was confused about why they didn't match.

**Important Takeaways:**

The main goal of continuing with the video was to gain awareness of what Sass is capable of. I realized that I’ll need more hands-on practice to effectively apply these features. Here are some key takeaways:

- **Partials**: Use an underscore (_) at the beginning of filenames that are meant to be imported.
- **Mixins**: Reusable functions created with `@mixin name(parameter) {}` and called using `@include name(parameter)`.
- **@extend**: Used for inheritance to share style rules.
- **& symbol**: References the parent selector for nesting.
- **Comments**: Use `/*! */` to ensure comments appear in the compressed output, while `//` is for general commenting.
- **Color functions**: `complement`, `lighten`, and `darken` help modify colors.
- **Lists**: Can be separated by commas or spaces and start at index 1.
- **@content**: Used inside mixins to inject content, useful for media queries or breakpoints.
- **...args**: Mixins can accept a variable number of arguments.
- **Loops**: Sass supports `@for`, `@each`, and `@while` for iteration.
- **Maps**: Work like dictionaries for key-value pairs.
- For more detailed info, referring to the official Sass documentation is recommended.
<br>

#### Career/Employability/Learning Insights:

The new material we’re covering in this subject is starting to feel quite overwhelming. In IT, everything seems to be interconnected, which makes the learning process far from straightforward. There’s also a lot of assumed prior knowledge, and I think that’s where I’m struggling—many courses build on concepts I’m not yet confident with. 

Even though it might take more time, I’ve realized that I need to approach each topic at my own pace, starting from what I do understand and gradually building on that. I found [this video](https://www.youtube.com/watch?v=s6dMWzZKjTs) really insightful—it emphasized the importance of learning with a clear roadmap instead of picking up random bits of knowledge.

Since front-end development is one of the career paths I’m considering, it’s important for me to fully grasp each part of the Sass tutorial on LinkedIn. I also want to be able to explain these concepts clearly to my group, especially because I’ve been assigned the front-end role in our team project.


