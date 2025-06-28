A simple, user-friendly web-based timer designed specifically to assist UPSC aspirants in their test preparation. This timer allows you to configure multiple time blocks, define repeats for each block, and set buffer times between them, all while providing audible announcements for key transitions.

Features
Multi-Stage Timer: Configure a sequence of distinct timers for different sections of your test practice.

Repeatable Timers: Set individual timers to repeat a specified number of times, perfect for practicing sets of questions or revision cycles.

Configurable Gap Time: Include buffer periods between timer blocks for breaks, review, or transitioning between tasks.

Audible Announcements: Get clear audio cues for:

"Starting Timer of {time}" - Announce the start of a new type of timer block (first run of a set).

"Time Started" - Announce the start of a subsequent repeat within the same timer block.

"Time's Up, Buffer Time" - Indicate the end of a timer block and the beginning of a gap period.

"All timers completed. Great job!" - A concluding announcement when the entire sequence finishes.

Real-time Clock: Displays the current Indian Standard Time (IST).

Announcement Log: Keeps a visual record of all spoken announcements with their timestamps.

Responsive Design: Optimized for use on both desktop and mobile browsers, ensuring a consistent experience across devices.

How to Use
The UPSC Test Timer is a single HTML file, making it incredibly easy to use.

Save the Code: Copy all the provided HTML code (including CSS and JavaScript) and save it as an .html file (e.g., upsc_timer.html) on your computer.

Open in Browser: Double-click the .html file, or open it with your preferred web browser (Chrome, Firefox, Edge, Safari, etc.).

Setting Up Your Timers
Upon opening the timer, you'll be on the Setup Page:

Number of Timers:

Use the "Number of Timers" input field or the " Add Another Timer" button to specify how many distinct timer blocks you want in your sequence. You can add up to 8 timers.

Configure Each Timer Block: For each timer card that appears:

Set Time (HH:MM:SS): Enter the duration for this specific timer block in Hours:Minutes:Seconds format (e.g., 00:30:00 for 30 minutes, 01:00:00 for 1 hour).

Repeats: Specify how many times this timer block should run before moving to the next timer in the sequence. For example, if you set it to 3, this 30-minute timer will run three times.

Gap Time (HH:MM:SS): Enter the buffer time that should occur after this timer block finishes, and before the next repeat (if any) or the next timer in the sequence begins. Format as Hours:Minutes:Seconds (e.g., 00:00:30 for a 30-second gap).

Start Timer: Once all your timer blocks are configured, click the " Start Timer" button.

During the Timer Session
After starting, you'll be on the Timer Page:

Main Timer Display: Shows the current countdown in HH:MM:SS format.

Current Sequence: Indicates which timer block is currently active (e.g., "Timer 1 - Run 1 of 3").

Timer State: Provides real-time status updates (e.g., "Timer is running", "Timer paused", "Buffer time").

Controls:

 Start: Resumes the timer if paused.

 Pause: Pauses the current countdown.

 Reset: Resets the entire timer sequence back to the beginning of the first configured timer.

 Back: Stops the current timer and returns you to the Setup Page to configure new timers.

Announcement Log: Displays a chronological list of all audible announcements made by the timer, along with their timestamps.

Important Notes
Browser Compatibility: This timer utilizes the Web Speech API for audible announcements. Ensure your browser supports this API (most modern browsers like Chrome, Firefox, Edge, Safari do).

Sound: Make sure your device's sound is turned on and not muted to hear the announcements.

Focus: For consistent performance and speech synthesis, it's recommended to keep the browser tab with the timer active and in focus.

Time Zones: The current time displayed is Indian Standard Time (IST), as specified in the code.

Input Format: Always enter time durations in the HH:MM:SS format (e.g., 00:05:00 for 5 minutes). If you only need minutes and seconds, you can use 00:MM:SS.

Development / Customization
The timer is built with pure HTML, CSS, and JavaScript, making it easy to customize:

HTML (index.html): Defines the structure and elements of the timer.

CSS (<style> tag): Controls the visual appearance and responsive behavior. You can modify colors, fonts, layout, etc.

JavaScript (<script> tag): Contains the core logic for timer functionality, announcements, and user interactions.

Feel free to modify the code to suit your specific needs, such as adding more complex announcement triggers, different visual themes, or advanced logging features.

Developed by @Hawk
UPSC Test Preparation Tool