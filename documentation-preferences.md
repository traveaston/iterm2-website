---
layout: default
title: Preferences - Documentation - iTerm2 - Mac OS Terminal Replacement
active-state: documentation
subhead: Preferences
---
<div class="doc-wrapper">
        {% include toc.html %}
	<section class="doc-section">
		<h6 class="question">General</h6>
		<hr>
		<h6 class="question">Open profiles window</h6>
		<p class="answer">
			If selected, the Profiles Window will automatically open when iTerm2 is started.
		</p>
		<h6 class="question">Open default window arrangement</h6>
		<p class="answer">
			If selected, the default saved window arrangement will be restored when iTerm2 starts. This is disabled if you haven't yet saved a window arrangement with Window > Save Window Arrangement. If you'd like iTerm2 to open without any windows, create an empty default window arrangement and turn this option on.
		</p>
		<h6 class="question">Quit when all windows are closed</h6>
		<p class="answer">
			If selected, iTerm2 will automatically quit when its last terminal window is closed.
		</p>
		<h6 class="question">Confirm closing multiple sessions</h6>
		<p class="answer">
			If selected, commands that close one session will not be confirmed, but commands that close multiple sessions (such as clicking the red button on a window with two or more tabs) will be confirmed with an alert box.
		</p>
		<h6 class="question">Confirm Quit iTerm2 Command</h6>
		<p class="answer">
			If selected, the Quit iTerm2 (cmd-Q) command will be confirmed if any terminal windows are open.
		</p>
		<h6 class="question">Only when multiple sessions close</h6>
		<p class="answer">
			If selected, commands that close one session will not be confirmed, but commands that close multiple sessions (such as clicking the red button on a window with two or more tabs) will be confirmed with an alert box.
		</p>
		<h6 class="question">Confirm Quit iTerm2 Command</h6>
		<p class="answer">
			If selected, the Quit iTerm2 (cmd-Q) command will be confirmed if any terminal windows are open.
		</p>
		<h6 class="question">Instant Replay Uses X MB per Session</h6>
		<p class="answer">
			This setting specifies the maximum amount of memory allocated to instant replay for each tab or split pane. More memory means instant replay is able to go farther back into the past. You can enter instant replay with View > Step Back in Time.
		</p>
		<h6 class="question">Save copy/paste history to disk</h6>
		<p class="answer">
			If selected, every time text is copied or pasted in iTerm2 it will be saved to disk. The last 20 values are recorded. They can be accessed with Edit > Open Paste History....
		</p>
		<h6 class="question">Add bonjour hosts to profiles</h6>
		<p class="answer">
			If selected, all bonjour hosts on the local network have a profile created for them as long as they're around.
		</p>
		<h6 class="question">Check for updates automatically</h6>
		<p class="answer">
			If enabled, iTerm2 will periodically check if a new version of iTerm2 exists, and if so it will prompt you to download and upgrade.
		</p>
		<h6 class="question">Prompt for test-release updates</h6>
		<p class="answer">
			If enabled, iTerm2 will periodically check if a new unstable version of iTerm2 exists, and if so it will prompt you to download and upgrade.
		</p>
		<h6 class="question">Load preferences from a custom folder or URL:</h6>
		<p class="answer">
			If enabled, iTerm2 will load its preferences from the specified folder or URL. After setting this, you'll be prompted when you quit iTerm2 if you'd like to save changes to the folder.
		</p>
		<h6 class="question">Copy to clipboard on selection</h6>
		<p class="answer">
			If enabled, text is copied to the clipboard immediately upon selection. If not selected, you must select Edit > Copy to copy it.
		</p>
		<h6 class="question">Copied text includes trailing newline</h6>
		<p class="answer">
			If enabled, a terminal newline will be copied to the pasteboard when the selection includes one; otherwise, no selection will ever include a terminal newline.
		</p>
		<h6 class="question">Allow clipboard access to terminal apps</h6>
		<p class="answer">
			If enabled, clipboard access will be granted via escape code to programs running in iTerm2. They will be able to retreive and set the contents of the system pasteboard.
		</p>
		<h6 class="question">Characters considered part of a word for selection</h6>
		<p class="answer">
			When you double-click in the terminal window, a "word" is selected. A word is defined as a string delimited by characters of a different class. The classes of characters are whitespace, word characters, and non-word characters. The characters in this field define the set of non-word characters.
		</p>
		<h6 class="question">Smart window placement</h6>
		<p class="answer">
			If enabled, new windows will be opened where they least overlap existing windows.
		</p>
		<h6 class="question">Adjust window when changing font size</h6>
		<p class="answer">
			If enabled, a change to a session's font will cause the window to grow or shrink.
		</p>
		<h6 class="question">Zoom button maximizes vertically only</h6>
		<p class="answer">
			If enabled, the green "Zoom" button expands a terminal window vertically but does not affect its width. This can be overridden by holding down shift while clicking the zoom button.
		</p>
		<h6 class="question">Closing hotkey window restores focus to last window, but may switch spaces.</h6>
		<p class="answer">
			If enabled, the act of closing a hotkey window will restore focus to the window that last had it. As a side effect, the current desktop/space may change.
		</p>
		<h6 class="question">Use Lion-style Fullscreen windows</h6>
		<p class="answer">
			If enabled, fullscreen windows will animate into a special desktop, as is typical in OS X 10.7 and later. If disabled, fullscreen windows will instantly go fullscreen without changing desktops.
		</p>
		<h6 class="question">When attaching, open unrecognized windows in...</h6>
		<p class="answer">
			When attaching to a new tmux session with the tmux integration, tmux windows not seen by iTerm2 before will open in either new windows or tabs, as specified by this preference.
		</p>
		<h6 class="question">Open dashboard if there are more than...tmux windows</h6>
		<p class="answer">
			When attaching to a tmux session with the tmux integration, windows are normally opened automaticaly. If there are too many of them, then the tmux dashboard is opened instead.
		</p>
		<h6 class="question">Automatically hide the tmux client session after connecting</h6>
		<p class="answer">
			When the tmux integration is entered by running tmux -CC, the window in which that command was run will miniaturize into the dock if this option is enabled.
		</p>
		<hr>
		<h6 class="question">Appearance</h6>
		<hr>
		<h6 class="question">Tab Style</h6>
		<p class="answer">
			Select from a list of tab looks.
		</p>
		<h6 class="question">Tab Position</h6>
		<p class="answer">
			Defines whether tabs appear at the top or bottom of a window.
		</p>
		<h6 class="question">Hide tab bar when there is only one tab</h6>
		<p class="answer">
			If selected, the tab bar will become invisible when a window contains exactly one tab.
		</p>
		<h6 class="question">Color tab labels on activity</h6>
		<p class="answer">
			If selected, tab labels become purple when a non-selected tab has new output, and red when a non-selected tab has output you haven't seen but that is not very recent.
		</p>
		<h6 class="question">Hide tab number and tab close button</h6>
		<p class="answer">
			If selected, only the tab name appears in a tab.
		</p>
		<h6 class="question">Hide tab activity indicator</h6>
		<p class="answer">
			If selected, the progress indicator in each tab will not be displayed.
		</p>
		<h6 class="question">Show tabs in fullscreen by holding cmd for</h6>
		<p class="answer">
			When in fullscreen mode, holding down the cmd key will cause the tab bar to show. This setting allows you to specify how long cmd must be held down before the tab bar is shown.
		</p>
		<h6 class="question">Show per-pane title bar with split panes</h6>
		<p class="answer">
			When a tab has split panes, this option controls whether each split pane will have its own title bar.
		</p>
		<h6 class="question">Auto-hide menu bar in non-Lion fullscreen</h6>
		<p class="answer">
			When Lion-style fullscreen is disabled, this option is in effect. If you'd like the menu bar to remain visible when a fullscreen window is present on a screen with a menu bar, turn this on.
		</p>
		<h6 class="question">Show window number</h6>
		<p class="answer">
			If selected, window titles include the window number. You can navigate to a window by pressing cmd-opt-N where N is the window number.
		</p>
		<h6 class="question">Show current job name</h6>
		<p class="answer">
			If selected, tab and window titles will show the name of the foreground job.
		</p>
		<h6 class="question">Show profile name</h6>
		<p class="answer">
			If selected, tab and window titles will show profile names.
		</p>
		<h6 class="question">Dimming affects only text, not background</h6>
		<p class="answer">
			When a window or pane is dimmed, this option controls whether the background color is dimmed or only the text colors.
		</p>
		<h6 class="question">Dimming amount</h6>
		<p class="answer">
			This slider controls how much to dim inactive windows or panes.
		</p>
		<h6 class="question">Dim inactive split panes</h6>
		<p class="answer">
			If selected, split panes that do not have keyboard focus will be slightly dimmed.
		</p>
		<h6 class="question">Dim background windows</h6>
		<p class="answer">
			If enabled, windows in the background (that is, those not receiving keyboard input) are dimmed according to the above settings.
		</p>
		<h6 class="question">Animate dimming</h6>
		<p class="answer">
			If enabled, window dimming effects are animated.
		</p>
		<h6 class="question">Show border around window</h6>
		<p class="answer">
			If selected, a 1-pixel border will be shown around the edges of terminal windows.
		</p>
		<h6 class="question">Hide scrollbar and resize control</h6>
		<p class="answer">
			If selected, the scrollbar and resize control (for OS 10.5 and 10.6) will not be visible.
		</p>
		<h6 class="question">Disable transparency for fullscreen windows by default</h6>
		<p class="answer">
			If enabled, entering fullscreen mode will automatically turn off transparency for that window.
		</p>
		<hr>
		<h6 class="question">Profiles > General</h6>
		<hr>
		<h6 class="question">Name</h6>
		<p class="answer">
			Gives the name of the profile which is shown in menus, preferences, and the profiles window.
		</p>
		<h6 class="question">Shortcut key</h6>
		<p class="answer">
			This shortcut can be used to open a new window or tab. By default, it opens a new tab, but if you hold down the option key while pressing the shortcut, a new window will be opened instead.
		</p>
		<h6 class="question">Tags</h6>
		<p class="answer">
			Tags are a collection of words or phrases that annotate a profile. When you search your profiles (for instance, in the profiles window), the tag names are searched in addition to the profile name.
		</p>
		<h6 class="question">Command</h6>
		<p class="answer">
			This is the command that is executed when a new session with the profile is created. If login shell is chosen, then your shell is run with '-' as the first character of argv[0]. You can put special terms surrounded by $$ in this field (example: $$USERNAME$$). When a new session is created, you will be prompted to enter a value for each such term. See the description of URL Schemes below for details about the special "$$" value that can go in this field.
		</p>
		<h6 class="question">Working directory</h6>
		<p class="answer">
			Normally, new sessions begin in your home directory. You can choose to open new sessions in the same directory as the current session (but only when creating a new tab), or you can specify a starting directory.
		</p>
		<h6 class="question">URL Schemes</h6>
		<p class="answer">
			You can configure a profile to handle a URL scheme, such as ssh. When a hyperlink is clicked on with that scheme, a new tab is opened with the selected profile. It is recommended that you set the command to "$$", in which case an ssh command line will be auto-generated. For other schemes, you can uses these variables in the Command field and they will be replaced with the appropriate part of the URL:
			<ul>
				<li>$$URL$$ The complete url</li>
				<li>$$HOST$$ The host portion of a url like scheme://host/</li>
				<li>$$USER$$ The username portion of a url like scheme://user@host/</li>
				<li>$$PASSWORD$$ The password portion of a url like scheme://user:password@host/</li>
				<li>$$PORT$$ The port number of a url like scheme://host:port/</li>
				<li>$$PATH$$ The path portion of a url like scheme://host/path</li>
				<li>$$RES$$ The portion of a url following the scheme.</li>
			</ul>
		</p>
		<hr>
		<h5>Profiles > Colors</h5>
		<hr>
		<p class="answer">
			Clicking on any of the color wells opens a color picker that lets you change the setting for the selected color.
		</p>
		<h6 class="question">Smart cursor color</h6>
		<p class="answer">
			When selected, a block cursor will be displayed in reverse video. If this would result in confusion, then a different color is chosen that will be most visible given the surrounding cells' background colors.
		</p>
		<h6 class="question">Minimum contrast</h6>
		<p class="answer">
			If text is displayed against a similar background color, the minimum contrast setting will move the text color towards black or towards white to ensure some minimum level of visibility. Setting this slider all the way to maximum will make all text black and white.
		</p>
		<h6 class="question">Load Presets</h6>
		<p class="answer">
			iTerm2 ships with some color presets, which you may load from this popup menu. You can import and export color presets to files with the extension "itermcolors". There is an online color gallery where users may share color presets, and a link to it is provided in this menu. When importing a color preset, the name it is assigned is based on the filename imported.
		</p>
		<hr>
		<h5>Profiles > Text</h5>
		<hr>
		<h6 class="question">Cursor</h6>
		<p class="answer">
			This lets you select a cursor shape.
		</p>
		<h6 class="question">Blinking cursor</h6>
		<p class="answer">
			If checked, the cursor will blink slowly to improve visibility.
		</p>
		<h6 class="question">Draw bold text in bold font</h6>
		<p class="answer">
			If selected, bold text will be drawn in a bold version of the selected font. If the font does not have a bold version, then a bold appearance is simulated by "double striking" the text: that is, drawing it twice, shifting it one pixel horizontally the second time.
		</p>
		<h6 class="question">Draw bold text in bright colors</h6>
		<p class="answer">
			If selected, bold text will be drawn in a bright version of its color.
		</p>
		<h6 class="question">Blinking text allowed</h6>
		<p class="answer">
			If selected, text with the blink attribute set will actually blink. Oh, the humanity.
		</p>
		<h6 class="question">Italic text allowed</h6>
		<p class="answer">
			If selected, text with the italic attribute set will be rendered in italics. The font you select must have an italic face.
		</p>
		<h6 class="question">Regular font</h6>
		<p class="answer">
			ASCII text (latin letters, numbers, and some symbols) will be drawn using this font. Select "Anti-aliased" to draw the text with smooth edges.
		</p>
		<h6 class="question">Non-ASCII font</h6>
		<p class="answer">
			All non-ASCII text (many accented Latin letters, non-Latin text, less-common symbols, and thousands of miscellaneous unicode characters) will be drawn with this font. It is recommended that you use the same point size for both regular and non-ASCII fonts. Select "Anti-aliased" to draw the text with smooth edges.
		</p>
		<h6 class="question">Treat ambiguous-width characters as double width</h6>
		<p class="answer">
			Some characters (e.g., Chinese ideograms) are double-width, and take two cells to display. Other characters (e.g., Latin letters) are single width and take only one cell to display. There is another category of characters known as "ambiguous width". One example of ambiguous-width characters are Greek letters. Depending on your application, you may prefer to display them as double-width or single-width. If most of the text you deal with is double-width, then you should enable this setting as it will help things to line up correctly in that context.
		</p>
		<hr>
		<h5>Profiles > Window</h5>
		<hr>
		<h6 class="question">Transparency</h6>
		<p class="answer">
			This sets the transparency of the window background. It can be temporarily disabled with View > Use Transparency.
		</p>
		<h6 class="question">Blur</h6>
		<p class="answer">
			If selected, the window background is blurred provided the background has some transparency. Selecting a large radius will blur the background more, but (especially on Retina displays) comes with a performance penalty.
		</p>
		<h6 class="question">Rows/Columns</h6>
		<p class="answer">
			When creating a new window with this profile, it will be created with this many rows and columns.
		</p>
		<h6 class="question">Background Image</h6>
		<p class="answer">
			This allows you to select an image to display behind the terminal's text. If Tile image is selected, then the image will be shown at its actual size and tesselated; otherwise, it will be stretched to fit the whole pane. The blending slider determines how strongly the image dominates over the text's background color.
		</p>
		<h6 class="question">Style</h6>
		<p class="answer">
			This defines the window style. Bottom- and Top-of-screen windows will disregard the columns setting. Left-of-screen windows will disregard the rows setting. Full-screen windows only respect the rows and columns setting when full-screen mode is exited.
		</p>
		<h6 class="question">Screen</h6>
		<p class="answer">
			If you have more than one screen connected, this lets you select the screen on which a new window should open. It is particularly useful for fullscreen and top-of-screen window styles.
		</p>
		<h6 class="question">Space</h6>
		<p class="answer">
			If you have enabled Spaces (or your OS uses Desktops instead of spaces) and have set Spaces/Mission Control to use Control+Number to switch spaces/desktops, then you can use this setting to select the initial space/desktop to open a new window using this profile.
		</p>
		<h6 class="question">If showing profile name in tab title, keep it when the title is changed</h6>
		<p class="answer">
			You can specify that profile names are shown in window and tab titles under Preferences > Appearance > Show Profile Name. If that is not set, then this option is irrelevant. When in use, a host may send an escape code that changes the window title. This setting causes the profile name to be preserved in that session-set title.
		</p>
		<h6 class="question">Disable session-initiated window resizing</h6>
		<p class="answer">
			If the host sends an escape code to resize the window, it will be ignored if this option is selected..
		</p>
		<hr>
		<h5>Profiles > Terminal</h5>
		<hr>
		<h6 class="question">Scrollback lines</h6>
		<p class="answer">
			The number of lines of scrollback buffer to keep above the visible part of the screen. Unlimited scrollback will allow it to grow indefinitely, possibly using all available memory.
		</p>
		<h6 class="question">Save lines to scrollback when an app status bar is present</h6>
		<p class="answer">
			Some programs (such as vim or tmux) keep a status bar at the bottom of the screen. For some applications (like vim) it is undesirable to save lines to the scrollback buffer when the application scrolls. For others (like tmux) you may want to save scrolled-off lines into the scrollback buffer. When this setting is enabled, lines scrolled off the top of the screen in the presence of a status bar are added to the scrollback buffer. The screen is considered to have a status bar if it has a scroll region whose top is the first line of the screen and whose bottom is above the bottom of the screen.
		</p>
		<h6 class="question">Save lines to scrollback in alternate screen mode</h6>
		<p class="answer">
			When in alternate screen mode, lines that scroll off the top of the screen will be saved to the scrollback buffer only if this option is enabled.
		</p>
		<h6 class="question">Character encoding</h6>
		<p class="answer">
			The encoding to send and receive in. For most people, "Unicode (UTF-8)" is the right choice.
		</p>
		<h6 class="question">Report terminal type</h6>
		<p class="answer">
			The TERM variable will be set to this value by default. If xterm-256color is selected and your system is missing the terminfo file, you will be prompted to install it when you open a new session.
		</p>
		<h6 class="question">Enable xterm mouse reporting</h6>
		<p class="answer">
			If selected, applications may choose to receive information about the mouse. This can be temporarily disabled by holding down Option.
		</p>
		<h6 class="question">Allow terminal to report window title</h6>
		<p class="answer">
			Programs running in a terminal may send an escape code to request the current window title. You may disable this feature by enabling this option. It should be disabled if you're communicating with an untrusted party, as there are possible injection attacks.
		</p>
		<h6 class="question">Use modern parser (experimental)</h6>
		<p class="answer">
			iTerm2 includes an experimental parser for CSI codes that should produce more correct results, but it isn't tested enough to be on by default. Enable this option to use it.
		</p>
		<h6 class="question">Disable session-initiated printing</h6>
		<p class="answer">
			If enabled, escape codes that initiate printing will be ignored.
		</p>
		<h6 class="question">Disable save/restore alternate screen</h6>
		<p class="answer">
			Some programs (such as vim, tmux, and less) switch into a so-called "alternate screen". A characteristic of this behavior is that when these programs terminate the screen's contents are restored to their state from before the program was run. If this option is selected, alternate screen mode is disabled and the screen cannot be restored by an application.
		</p>
		<h6 class="question">Silence bell</h6>
		<p class="answer">
			If selected, the bell (control-G) will not make an audible sound.
		</p>
		<h6 class="question">Enable Growl notifications</h6>
		<p class="answer">
			If selected and Growl is installed, iTerm2 will post a Growl notification when sessions receive output, become idle, ring the bell, or close.
		</p>
		<h6 class="question">Flash visual bell</h6>
		<p class="answer">
			If selected, a bell graphic will be flashed when the bell character is received.
		</p>
		<h6 class="question">Show bell icon in tabs</h6>
		<p class="answer">
			If selected, tabs will indicate that a bell has rung by displaying a bell graphic.
		</p>
		<h6 class="question">Set locale variables automatically</h6>
		<p class="answer">
			If enabled, LANG and LC_CTYPE ennvironment variables will be set based on your machine's language settings.
		</p>
		<hr>
		<h5>Profiles > Session</h5>
		<hr>
		<h6 class="question">Automatically close a session when it ends</h6>
		<p class="answer">
			If selected, a session's pane, tab, or window will automatically close when the session ends.
		</p>
		<h6 class="question">Prompt before closing</h6>
		<p class="answer">
			When a session will close, you can choose when to be prompted with a modal alert.
		</p>
		<h6 class="question">Automatically log session input to files in:</h6>
		<p class="answer">
			If enabled, every session's output will be logged to a file in the specified directory. File names are formatted as Date_Time.ProfileName.TerminalID.ProcessId.RandomNumber.log.
		</p>
		<h6 class="question">When idle, send ASCII code</h6>
		<p class="answer">
			If selected, the specified ASCII code will be transmitted every 30 seconds while nothing is happening. Don't use this unless you know what you're doing as it can have unexpected consequences.
		</p>
		<hr>
		<h5>Profiles > Keys</h5>
		<hr>
		<p class="answer">
			This panel shows key mappings. You can double-click on a mapping to edit it. When the "Keyboard Shortcut" field has focus, you should press the keystroke that you want to modify (even if it involves modifiers like Cmd). The following actions are available:
		</p>
		<h6 class="question">Ignore</h6>
		<p class="answer">
			The keypress will do nothing.
		</p>
		<h6 class="question">Do not remap modifiers</h6>
		<p class="answer">
			If modifier remapping is in effect (set under Preferences > Keys), it can be disabled for certain key combinations. When you choose this action, modifier remapping is temporarily disabled so you can press the key combination unremapped in the key field.
		</p>
		<h6 class="question">Remap modifiers in iTerm2 only</h6>
		<p class="answer">
			If modifier remapping is in effect (set under Preferences > Keys), it can be set to not affect other applications that may listen for global hotkeys. When you choose this action, modifier remapping is temporarily disabled so you can press the key combination unremapped in the key field.
		</p>
		<h6 class="question">Split/New Window/Tab with Profile</h6>
		<p class="answer">
			These actions allow you to create a new session with a specified profile when a key is pressed.
		</p>
		<h6 class="question">Backward in Time/Forward in Time</h6>
		<p class="answer">
			This is equivalent to the menu item View > Step Backward/Forward in Time
		</p>
		<h6 class="question">Cycle Tabs Forward</h6>
		<p class="answer">
			This implements tab switching the same way Cmd-Tab switches windows, with the most-recently-used stack.
		</p>
		<h6 class="question">Next/Previous Tab/Window</h6>
		<p class="answer">
			These actions navigate among tabs and windows.
		</p>
		<h6 class="question">Move tab left/right</h6>
		<p class="answer">
			Changes the tab's position in the order.
		</p>
		<h6 class="question">Scroll to End/Top/Up/Down</h6>
		<p class="answer">
			These actions move through the scrollback buffer.
		</p>
		<h6 class="question">Select Split Pane Above/Below/Left/Right</h6>
		<p class="answer">
			These actions navigate split panes.
		</p>
		<h6 class="question">Send ^? / ^H Backspace</h6>
		<p class="answer">
			Modern systems use ^? for backspace, while some legacy systems use ^H.
		</p>
		<h6 class="question">Send Escape Sequence</h6>
		<p class="answer">
			This action allows you to enter some text that will be sent when the associated key is pressed. First, the ESC character is sent, and then the text you entered is sent.
		</p>
		<h6 class="question">Send Hex Code</h6>
		<p class="answer">
			This action allows you to enter a sequence of hex codes that will be sent. Each value should begin with "0x" followed by one or two hex digits (0-9, a-f, or A-F). Each code should be separated by a space. You can see a list of hex codes on http://asciitable.com/ in the "Hx" column.
		</p>
		<h6 class="question">Send Text</h6>
		<p class="answer">
			This action allows you to enter a text string that will be sent when the associated key is pressed. The following escape characters are supported: \n (newline), \e (escape), \a (bell), \t (tab).
		</p>
		<h6 class="question">Toggle Fullscreen</h6>
		<p class="answer">
			This action enters or exits full screen mode.
		</p>
		<h6 class="question">Run Coprocess</h6>
		<p class="answer">
			This action launches a Coprocess. <a href="documentation-coprocesses.html">Learn more about coprocesses</a>.
		</p>
		<h6 class="question">Select Menu Item...</h6>
		<p class="answer">
			This action allows you to enter the name of an iTerm2 menu item. It must be entered exactly the same as it appears in the menu. Ellipses can be typed with option-semicolon.

			You can add a new keymapping by pressing "+". You can remove an existing mapping by selecting it and pressing "-". Three presets are provided: "Xterm defaults" is the normal key mappings, while "Xterm defaults with numeric keypad" disables the "application keypad" in favor of the numbers and symbols that the numeric keypad typically emits. "Terminal.app Compatability" tries to emulate the way that Terminal.app sends keys by default.
		</p>
		<h6 class="question">Left/Right Option Key Acts As</h6>
		<p class="answer">
			It is common to use a modifier to send so-called "meta keys". For most users, selecting "+Esc" here is the right choice. The "Meta" option sets the high bit of the input character, and is not compatible with modern systems.
		</p>
		<h6 class="question">Delete sends ^H</h6>
		<p class="answer">
			If you are on a legacy system that does not accept ^? for backspace, select this and it will add a key mapping for you.
		</p>
		<hr>
		<h5>Profiles > Advanced</h5>
		<hr>
		<h6 class="question">Triggers</h6>
		<p class="answer">
			Triggers are actions that are performed when text matching a regular expression is received. Each trigger has a regular expression, which defines when it runs. It has an action, which defines what it performs, and it has an optional parameter, whose meaning depends on the action. When the parameter is textual, \0 is replaced with the entire match, and \1...\9 are replaced with match groups.
		</p>
		<h6 class="question">Action: Bounce Dock Icon</h6>
		<p class="answer">
			This action causes the dock icon to bounce when text matching the trigger is received. The dock icon only bounces if iTerm2 is in the background.
		</p>
		<h6 class="question">Action: Highlight Text</h6>
		<p class="answer">
			The text matching the regex in the trigger will change color. The parameter sets the color.
		</p>
		<h6 class="question">Action: Ring Bell</h6>
		<p class="answer">
			The system bell rings when text matching the trigger is received.
		</p>
		<h6 class="question">Action: Run Command</h6>
		<p class="answer">
			When text matching the trigger is received, a command is executed. Its output is dropped. The parameter gives the command to run.
		</p>
		<h6 class="question">Action: Run Coprocess</h6>
		<p class="answer">
			When text matching the trigger is received, a coprocess is started. The parameter gives a command to run as the coprocess.
		</p>
		<h6 class="question">Action: Run Silent Coprocess</h6>
		<p class="answer">
			When text matching the trigger is received, a silent coprocess is started. A silent coprocess differs from a regular coprocess in that input goes only to the coprocess and not to the terminal display. This is useful, for example, for ZModem transfers. The parameter gives a command to run as the coprocess.
		</p>
		<h6 class="question">Action: Send Growl Alert</h6>
		<p class="answer">
			When text matching the trigger is received, a growl alert is posted with the text inthe parameter.
		</p>
		<h6 class="question">Action: Send Text</h6>
		<p class="answer">
			When text matching the trigger is received, text in the parameter is written to the terminal.
		</p>
		<h6 class="question">Action: Show Alert</h6>
		<p class="answer">
			When text matching the trigger is received, a modal alert is shown with text in the parameter.
		</p>
		<h6 class="question">Smart Selection</h6>
		<p class="answer">
			Smart selection allows you to define a set of regular expressions, each with an assigned priority, that are used for making the best possible selection. By default, a quad-click invokes smart selection. Smart selection is described in full in the Smart Selection document.
		</p>
		<h6 class="question">Semantic History</h6>
		<p class="answer">
			Semantic history is used to open a file when you Cmd-Click on it. The current working directory for each line in the terminal is tracked to help find files. If Semantic History is set to "Open with default app," then files are passed to the OS to be opened with whatever is associated. Alternatively, you can choose "Open URL..." to open a specific URL (with \1 replaced with the filename and \2 replaced with the line number, if applicable). If you choose "Open with editor..." then text files will be opened with the designated editor, while other files are opened with the default app for their file type. For more flexibility, choose "Run command..." and specify a command to execute. \1 will be replaced with the file name, \2 will be replaced with the line number (if applicable), \3 with text in the line prior to the click location, \4 with text in the line subsequent to the click location, and \5 for the working directory of the line clicked on. Finally, "Always run command..." is like "Run command...," but takes effect even if the object clicked on is not an existing filename.
		</p>		
		<hr>
		<h5>Keys</h5>
		<hr>
		<h6 class="question">Remap modifier keys</h6>
		<p class="answer">
			iTerm2 allows you to change the meanings of the modifier keys only within iTerm2. This is useful, for example, if you find it difficult to press "option" for "meta" and would prefer to use "command" for that purpose.
		</p>
		<h6 class="question">To switch tabs</h6>
		<p class="answer">
			Tabs are normally navigated with cmd+number, but you can change the modifier used for that function here.
		</p>
		<h6 class="question">To switch windows</h6>
		<p class="answer">
			Windows are normally navigated with cmd+opt+number, but you can change the modifier used for that function here.
		</p>
		<h6 class="question">Show/Hide iTerm2 with a system-wide hotkey</h6>
		<p class="answer">
			When enabled, you can focus the Hotkey: field and press a keystroke. From then on, pressing that keystroke (even when iTerm2 is not the front application) will cause iTerm2 to come to the front. If it is the foreground app, it will be sent to the back. This requires that you enable access for assistive devices in the Universal Access panel of System Preferences.
		</p>
		<h6 class="question">Hotkey toggles a dedicated window with profile</h6>
		<p class="answer">
			If enabled, the hotkey set above will toggle a single window with a specific profile. This provides an always-available terminal.
		</p>
		<h6 class="question">Global shortcut keys</h6>
		<p class="answer">
			This interface works like the keyboard shortcut system in profiles (described above) but it affects all profiles. Settings here are overridden by those in a profile's key mappings.
		</p>
		<hr>
		<h5>Pointer</h5>
		<hr>
		<h6 class="question">Mouse Button and Trackpad Gesture Actions</h6>
		<p class="answer">
			You may assign custo actions to mouse clicks and trackpad gestures. The left mouse button is not configurable because its behavior is rather complex, however. This is especially useful if you have a mouse with many buttons. Any combination of mouse button + number of clicks + modifiers may be assigned an action. For gestures, three finger taps and swipes may be configured in combination with modifiers. The following actions are available:
		</p>
		<h6 class="question">Extend selection</h6>
		<p class="answer">
			The text selection will grow, either from its beginning or end, to the location of the pointer.
		</p>
		<h6 class="question">Move pane</h6>
		<p class="answer">
			The current pane will turn green. Click in another window's tab bar or in another pane to split to move the now-green pane.
		</p>
		<h6 class="question">New Horizontal/Vertical split with profile</h6>
		<p class="answer">
			The pane under the pointer will be split and the new split will use the specified profile.
		</p>
		<h6 class="question">New Window With Profile</h6>
		<p class="answer">
			A new window will be opened with the specified profile.
		</p>
		<h6 class="question">Next/Previous Tab/Window</h6>
		<p class="answer">
			Navigates through tabs and windows.
		</p>
		<h6 class="question">Open Context Menu</h6>
		<p class="answer">
			Opens the menu normally opened by a right click.
		</p>
		<h6 class="question">Open URL in background</h6>
		<p class="answer">
			Opens the URL under the pointer in your web browser without bringing the browser to the foreground.
		</p>
		<h6 class="question">Open URL/Semantic History</h6>
		<p class="answer">
			Opens the URL under the pointer, bringing the web browser to the foreground. If what's under the cursor is a filename on the local machine, it will be opened with Semantic History.
		</p>
		<h6 class="question">Paste from Clipboard</h6>
		<p class="answer">
			This is identical to Edit > Paste.
		</p>
		<h6 class="question">Paste from Selection</h6>
		<p class="answer">
			Pastes the most recent selection made in iTerm2, even if it's not what's in the pasteboard.
		</p>
		<h6 class="question">Select Next/Previous Pane</h6>
		<p class="answer">
			Navigates panes according to how recently they were used.
		</p>
		<h6 class="question">Select pane Above/Below/Left/Right</h6>
		<p class="answer">
			Navigates panes by their layout.
		</p>
		<h6 class="question">Send Escape Sequence...</h6>
		<p class="answer">
			This action allows you to enter some text that will be sent when the associated key is pressed. First, the ESC character is sent, and then the text you entered is sent.
		</p>
		<h6 class="question">Send Hex Code</h6>
		<p class="answer">
			This action allows you to enter a sequence of hex codes that will be sent. Each value should begin with "0x" followed by one or two hex digits (0-9, a-f, or A-F). Each code should be separated by a space. You can see a list of hex codes on http://asciitable.com/ in the "Hx" column.
		</p>
		<h6 class="question">Send Text</h6>
		<p class="answer">
			This action allows you to enter a text string that will be sent when the associated key is pressed. The following escape characters are supported: \n (newline), \e (escape), \a (bell), \t (tab).
		</p>
		<h6 class="question">Smart Selection</h6>
		<p class="answer">
			Performs smart selection on the text under the pointer.
		</p>
		<h6 class="question">Smart Selection ignoring Newlines</h6>
		<p class="answer">
			Performs smart selection on the text under the pointer, ignoring newlines (e.g., if a URL is split by a hard newline, it can still be selected as a single item).
		</p>
		<h6 class="question">Focus follows mouse</h6>
		<p class="answer">
			If enabled, moving the mouse over an inactive window will cause it to receive keyboard focus.
		</p>
		<h6 class="question">Cmd-Click Opens Filename/URL</h6>
		<p class="answer">
			If enabled, then clicking on a filename (of an existing file on the local machine) or a URL will open it.
		</p>
		<h6 class="question">Report ctrl-click to apps instead of opening menu</h6>
		<p class="answer">
			If enabled, ctrl-click will be sent to applications that support Xterm mouse reporting (if mouse reporting is enabled).
		</p>
		<h6 class="question">Three-finger tap reports middle click to apps</h6>
		<p class="answer">
			If enabled, a three-finger tap acts like a middle click for the purposes of mouse reporting.
		</p>
		<h6 class="question">Triple-click selects full wrapped lines</h6>
		<p class="answer">
			If enabled, a triple click selects a whole line, even if it was longer than one row in the terminal. If off, then triple click selects exactly one row.
		</p>
		<h6 class="question">Middle button pastes from clipboard</h6>
		<p class="answer">
			If enabled, clicking the mouse's middle button will paste. Otherwise, it may be reported to the application if Xterm mouse reporting is on and the application supports it.
		</p>
		<hr>
		<h5>Arrangements</h5>
		<hr>
		<p class="answer">
			This tab lets you view saved window arrangements. You can delete them with the minus button and select the default arrangement.
		</p>
	</section>
</div>