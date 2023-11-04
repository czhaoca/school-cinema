# Setup Instructions

This document provides instructions for setting up a local environment to run the legacy Flash website and guidance for renovating the website to be compatible with HTML5.

## Running the Legacy Website

Due to the discontinuation of Flash support in modern browsers, running the legacy website can be challenging. However, you can use a few methods to view and interact with the SWF content for educational or archival purposes.

### Option 1: Using a Flash-compatible Browser

Some browsers or browser versions still allow you to enable and run Flash content. Follow these steps:

1. **Find a browser that still supports Flash:** Some older versions of browsers like Firefox or Internet Explorer may still allow you to run Flash.
   
2. **Install the browser:** Make sure it's a version that supports Flash.

3. **Install Flash Player:** You may need to download a version of Adobe Flash Player that is compatible with the browser you've chosen.

4. **Change Browser Settings:** Often, you will have to adjust the browser's security settings to allow Flash content to run, as modern security protocols disable it by default.

5. **Open the Website Locally:** You can then open the `index.html` file or set up a local server to view the website.

### Option 2: Using Flash Emulators

Flash emulators like Ruffle can emulate Flash content in a web browser without requiring the actual Flash plugin. Here's how to set it up:

1. **Download Ruffle:** Visit the [Ruffle website](https://ruffle.rs/) and download the appropriate version for your system.

2. **Integrate with Your Browser:** Follow the instructions on the Ruffle website to integrate it with your browser.

3. **Open the Website:** Open the `index.html` in your browser to view the content.

## Renovating the Website to HTML5

To update the website to HTML5, follow these general steps:

1. **Assess the Content:** Understand the scope of the content that needs to be converted from Flash to HTML5, including animations, media, and ActionScript code.

2. **Set Up Your Development Environment:**
   - Install a code editor like Visual Studio Code.
   - Install Git for version control.
   - Set up a local web server for testing (you can use Node.js with Express, for example).

3. **Extract Assets from SWF:**
   - Use a tool like JPEXS Free Flash Decompiler to extract assets from your SWF files.
   - Organize the assets into folders within your project.

4. **Recreate Layout and Design:**
   - Use HTML and CSS to replicate the layout of the original Flash website.
   - Ensure your design is responsive and works on various devices and screen sizes.

5. **Convert Flash Animations:**
   - Use a combination of JavaScript and CSS to recreate the animations.
   - Alternatively, consider using animation libraries such as GSAP (GreenSock Animation Platform) for complex animations.

6. **Reprogram Interactivity:**
   - Rewrite ActionScript to JavaScript. This will likely be the most time-consuming step as it requires not just direct translation, but rethinking the logic to fit within the modern web paradigm.
   - Test all interactive elements to ensure they work as expected.

7. **Update Media Formats:**
   - Convert .flv video files to .mp4 or other web-compatible formats.
   - Convert audio to widely supported formats like MP3.

8. **Testing:**
   - Test the website across all modern browsers for compatibility.
   - Ensure that performance and functionality match the original Flash version as closely as possible.

9. **Deployment:**
   - Once testing is complete and you are satisfied with the HTML5 version, deploy it to a web server.
   - Update any documentation to reflect the changes.

For a detailed guide on each of these steps, it's recommended to consult web development tutorials that focus on converting Flash to HTML5, as each website will present unique challenges and solutions.

---

By following these instructions, you should be able to access and interact with the legacy Flash content or begin the process of updating the website to modern web standards. Good luck!
