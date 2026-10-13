# 🔔 Digital Bell System

### A Smart, Flexible and User-Friendly School Bell Management System

A browser-based school bell management system designed to automate daily bell schedules, manage school timetables, play customized audio recordings, and handle unexpected timetable changes.

Developed as part of a **School Digitalization Initiative**, this project aims to reduce manual bell operations and make school administration simpler and more efficient.

---

## ✨ Key Features

### 1. Automated School Bell System

- Automatically plays scheduled bell sounds.
- Supports eight teaching periods.
- Includes interval and register-marking reminders.
- Displays upcoming bell events.
- Provides Start and Stop controls.
- Supports customized audio for individual periods.

### 2. Morning Audio System

A separate morning audio system allows schools to schedule their morning activities.

| Morning Audio | Default Time |
|---|---|
| Morning Song | 7:21 AM |
| Morning Bell 1 | 7:25 AM |
| Morning Bell 2 | 7:30 AM |

**Features:**
- Separate **Start morning audio** button.
- Separate **Stop morning audio for today** button.
- Editable morning audio timings.
- Custom audio uploads for each event.
- Morning events displayed on the daily timeline.

**Important:** Morning audio scheduling is controlled separately from the regular bell system.

### 3. Prayer Ran Late — Automatic Timetable Recalculation

One of the main features of this project is its ability to adjust the school timetable when morning prayer or assembly finishes later than expected.

**How it works:**

1. Click **Prayer ran late**.
2. Enter the new starting time of Period 1.
3. Confirm the school's departure time.
4. Click **Confirm & Recalculate**.
5. The system automatically updates the timetable.

The recalculation:
- Preserves the selected school departure time.
- Maintains the configured interval duration.
- Maintains the register-marking duration.
- Redistributes available teaching time across eight periods.
- Updates the daily timeline automatically.

**Example:**

If Period 1 normally begins at 7:50 AM but morning prayer finishes at 8:10 AM, the administrator can enter the new starting time.

The system recalculates the remaining teaching periods without unnecessarily extending the school day.

### 4. Customizable School Timetable

Schools can modify their daily schedules using **View Timetable**.

Configurable settings include:
- Period starting times and durations.
- Interval duration.
- Register-marking duration.
- School departure time.
- Morning audio timings.
- School hymn timing.
- Active school days.

The updated schedule is reflected in the daily timeline.

### 5. School Hymn Management

The system includes optional school hymn playback.

**Default scheduled time: 1:33 PM**

When starting the regular bell system, the application asks whether the school hymn should be played.

Administrators can:
- Enable or skip the school hymn.
- Upload a custom school hymn recording.
- Modify the hymn time through **View Timetable**.
- View the hymn event in the daily timeline.

If the school hymn is disabled for the day, it is not scheduled to ring.

### 6. Flexible Timetable Adjustments

Administrators can adjust the remaining school schedule without manually editing every period.

Available options include:
- Move remaining bells five minutes earlier.
- Delay remaining bells by five or ten minutes.
- Apply custom time adjustments.
- Restore the normal timetable.

These controls are intended for smaller adjustments during the school day.

### 7. Custom Audio Management

Schools can use their own audio recordings instead of relying only on default sounds.

The system supports custom audio for:
- Morning Song.
- Morning Bell 1.
- Morning Bell 2.
- Period 1 through Period 8.
- Register-marking reminder.
- Interval bells.
- School Hymn.

The **Audio files** section allows users to select audio recordings for the available events.

The system also provides volume controls and built-in chimes for supported bell events when custom audio cannot be played.

### 8. Real-Time Dashboard

The dashboard displays:
- Current date and time.
- Bell system status.
- Next scheduled bell.
- Countdown to the next bell.
- Today's bell timeline.
- Recently played bell events.

### 9. Virtual Clock

The application includes a virtual clock for testing and manual time adjustment.

Users can:
- Set a custom date.
- Set a custom time.
- Simulate bell events.
- Test timetable changes.
- Return to the normal PC clock.

**Important:** Return to **Use PC Clock** before normal school operation unless a virtual clock is intentionally required.

### 10. Light and Dark Modes

The application provides both light and dark interface themes for comfortable operation.

---

## 🚀 Installation Guide — Read Before Using

**We recommend downloading the complete project as a ZIP file before configuring the bell system.**

This keeps a local copy of the application and its supporting files on the school computer.

### Step 1: Download the Complete Project

1. Visit the official GitHub repository:

   https://github.com/Jegathayini/digital_bell_system

2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Wait until the ZIP file has downloaded.
5. Open the Downloads folder.
6. Right-click the downloaded ZIP file.
7. Select **Extract All**.
8. Choose a suitable permanent location, such as Documents.
9. Open the extracted project folder.

**Do not run the application directly from inside the ZIP file. Extract it first.**

### Step 2: Open the Application

1. Find `index.html` inside the extracted folder.
2. Right-click the file.
3. Select **Open with**.
4. Choose Google Chrome or Microsoft Edge.
5. The Digital Bell System dashboard will open.

No programming knowledge is required for normal use.

### Step 3: Configure the School Timetable

1. Click **View Timetable**.
2. Check all eight period timings.
3. Configure the interval and register-marking duration.
4. Confirm the school departure time.
5. Check the morning audio timings.
6. Set the school hymn time.
7. Select the required school days.
8. Save the timetable settings.

### Step 4: Add Your Own Audio Files

The downloaded project may not include school-specific audio recordings.

Each school should configure its own audio files before starting the bell system.

**Method A — Add Audio Through the Website (Recommended)**

1. Open the Digital Bell System.
2. Click **Audio files**.
3. Locate the required audio event.
4. Choose the audio upload option.
5. Select an audio file from your computer.
6. Repeat for the other required audio events.
7. Test the selected sounds using the available playback controls.
8. Close the audio settings.
9. **Reload the website after adding the audio files.**
10. Open **Audio files** again and verify the selected recordings.

MP3 files are recommended for compatibility.

**Important:** Audio selected through the website is handled by the browser's existing audio configuration. It is not automatically copied into the project's `audios` folder.

Keep the original audio recordings safely stored on the school computer.

**Method B — Add Audio to the Project Folder**

The application also references predefined audio files inside the `audios` folder.

Users familiar with file management can place recordings in this folder using the expected filenames.

Example:

```text
digital_bell_system/
│
├── index.html
├── README.md
│
└── audios/
    ├── morning_song.mp3
    ├── audio_1.mp3
    ├── audio_2.mp3
    ├── school_hymn.mp3
    ├── 1st_period.mp3
    ├── 2nd_period.mp3
    └── ...
```

The names above are examples of filenames recognized by the current application. Other bell events also have their own expected filenames.

When using this method:

1. Keep the audio files inside the `audios` folder.
2. Use the filenames expected by the application.
3. Do not rename `index.html`.
4. Keep the folder structure unchanged.
5. Reload the website after adding or replacing files.
6. Test the recordings before normal operation.

**Note:** This folder method applies to the extracted local project. Adding files to a local folder does not update the public GitHub Pages website.

### Step 5: Reload and Verify

After configuring the timetable and audio:

1. Reload the website using **Ctrl + R**.
2. Open **View Timetable** and check the saved schedule.
3. Open **Audio files** and verify the recordings.
4. Test the sound output.
5. Confirm that the correct PC clock is being used.
6. Start the required bell systems.

If audio assignments are missing after reloading, select the files again and verify that they play. Browser storage may behave differently depending on the browser and how the application was opened.

### Step 6: Start the Bell System

**For Morning Audio**

1. Click **Start morning audio**.
2. Confirm the morning schedule.
3. Keep the website open.

**For Regular School Bells**

1. Click **Start bell system**.
2. Choose whether to play the school hymn.
3. Confirm the selection.
4. Monitor the upcoming bell timeline.

After every website reload or computer restart, check the system status and start the required bell systems again.

---

## 🖥️ Recommended Daily Operating Procedure

Before school begins:

- [ ] Turn on the school computer.
- [ ] Connect and test the speakers.
- [ ] Open the Digital Bell System.
- [ ] Check the computer date and time.
- [ ] Verify the school timetable.
- [ ] Check the required audio recordings.
- [ ] Start the morning audio system.
- [ ] Start the regular bell system when appropriate.
- [ ] Confirm the school hymn preference.
- [ ] Keep the computer awake and the website open.

---

## ⚠️ Important Guidelines

### Computer Power and Sleep

The application requires an active browser and computer to operate reliably.

- Keep the computer powered on.
- Prevent automatic sleep during school hours.
- Keep the application open.
- Avoid closing the browser while bells are scheduled.
- Check the system after power interruptions or restarts.

**The application cannot guarantee scheduled playback while the computer is sleeping, shut down, or the browser is closed.**

### Audio Playback

- Make sure the speakers are connected.
- Check the system volume.
- Check the application's volume settings.
- Do not mute the browser tab.
- Test important recordings before school starts.
- Use audio files that the school has permission to play.

### Browser Storage

Some application settings and uploaded audio information are stored using browser storage.

To reduce the risk of losing settings:

- Use the same browser and browser profile.
- Avoid clearing website data unnecessarily.
- Keep backup copies of the original audio recordings.
- Recheck audio assignments after updates or browser changes.
- Do not assume uploaded audio will automatically transfer to another computer.

### Reloading the Website

**After adding or replacing audio files, reload the website and verify the recordings before starting the bell system.**

Reloading may stop the currently running bell system. Start it again after checking the settings.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | User interface and responsive design |
| JavaScript | Timetable calculations and automation |
| Web Audio API | Bell sound generation and playback |
| Browser Storage | Supported settings and audio configuration |
| GitHub Pages | Free static website hosting |

The system does not require a dedicated backend server for its core functionality.

---

## 📁 Project Structure

```text
digital_bell_system/
│
├── index.html          # Main application
├── README.md           # Documentation
│
└── audios/             # Optional local audio files
```

---

## 🌐 Online Access

The project is also designed for browser-based access through GitHub Pages.

**GitHub Repository:**

https://github.com/Jegathayini/digital_bell_system

**GitHub Pages:**

https://jegathayini.github.io/digital_bell_system/

For school installation, downloading the complete project ZIP is recommended so that a local copy is available.

---

## 🔧 Troubleshooting

| Problem | Suggested Solution |
|---|---|
| Bell does not ring | Check whether the bell system has been started |
| No audio output | Check speaker connection, browser audio permission and volume |
| Morning song does not play | Check the audio assignment and start morning audio |
| School hymn does not play | Check its audio file, scheduled time and daily preference |
| Wrong bell time | Check the timetable and computer clock |
| Audio missing after reload | Re-select the recording and test it |
| Bell stops after PC sleeps | Keep the computer awake during school hours |
| Timetable changes unexpectedly | Review prayer recalculation and manual adjustments |

---

## 🎯 Project Objectives

The Digital Bell System aims to:

- Reduce manual school bell operations.
- Improve daily timetable management.
- Simplify adjustments caused by morning prayer delays.
- Support customized school audio recordings.
- Reduce administrative workload.
- Provide an accessible, user-friendly school management tool.
- Contribute to school digitalization.

---

## 🔮 Future Improvements

Potential future enhancements include:

- More reliable background scheduling.
- Automatic startup with the school computer.
- Improved audio backup and restoration.
- Bell activity reports.
- Better recovery after unexpected shutdowns.
- Integration with other school management systems.

---

## 👩‍💻 Developed By

**Jegathayini Thiruchchelvam**

GitHub: https://github.com/Jegathayini

Project: [Digital Bell System](https://github.com/Jegathayini/digital_bell_system)

Developed as part of a School Digitalization Initiative.

---

**Digital Bell System — Making School Scheduling Smarter, Simpler and More Efficient.**
