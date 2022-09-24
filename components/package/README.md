# React Simple Scroll Reveal

React Simple Scroll Reveal is an animation framework for React. [DEMO](https://reactscrollrevealdemo.netlify.app/)

# Installation

In the command prompt run:

> npm install react-simple-scroll-reveal

Alternatively you may use yarn:

> yarn add react-simple-scroll-reveal

## Usage

Import React Simple Scroll Reveal to your React component:

```Javascript
import ScrollReveal from "react-simple-scroll-reveal";
```

Then wrap the components you want to animate:

```Javascript
<ScrollReveal anim="your_animation_class_name">
    <h2>Beautiful Mind</h2>
</ScrollReveal>
```

### Props

To alter the behavior of the animation components, you may supply the following properties to them:
| Prop | Description | Values | Default |
|:------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------:|:---------:|
| anim | Add classes to animate in element. | string | undefined |
| cascade | Reveal list items with automatically assigned time intervals. | boolean | false |
| margin | Reveal the element after X pixel passing it. | number | 0 |
| threshold | Value between 0 and 1 which indicate at what percentage of the target's visibility the observer's callback should be executed. | between 0 and 1 | 0 |
| duration | The animation duration (seconds). | number | 1 |
| delay | Waiting X second(s) till the animation begins. | number | 0 |
| damping | A factor that influences the delay allocated to each animated component in a cascade animation. | number | 1 |
| triggerOnce | Specifies whether the animation should be performed only once. | boolean | false |
| containerClassName | Add a new class name to the container. | string | undefined |
| root | A Element or Document object whose bounding box is used as the bounds of the viewport for the purposes of determining how much of the target element is visible. | | null |
