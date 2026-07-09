# Typing Effect with Cursor

## What does this code do?

This example demonstrates a **CSS-based typing effect** that simulates text being typed character by character with a blinking cursor. It uses CSS `steps()` animation for smooth character reveal and a `border-right` element for the cursor animation.

## What problem does it solve?

Typing effects add dynamic, human-like behavior to static text, making interfaces feel more alive and engaging. This is commonly used in:
- Hero headlines on landing pages
- Chat message interfaces
- Code snippet displays
- Portfolio websites

## How to use this?

Simply use the `.typing-effect` class in your HTML:

```html
<div class="card">
    <p>I'm sky :<span class="typing-effect"></span></p>
</div>

The typing effect will automatically animate when the page loads. You can customize:

Animation duration: Adjust animation-duration in CSS
Text content: Change the text inside the span
Cursor color: Modify the border-color in .typing-effect
Features
    Pure CSS animation using steps() timing function
    Blinking cursor effect with @keyframes blink
    Lightweight and reusable
    No external dependencies
    Browser compatible (Chrome, Firefox, Safari, Edge)

Example
Open demo.html in your browser to see multiple typing effect examples including headlines, code snippets, and chat messages.
