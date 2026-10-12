# 🔔 Digital Bell System

**A Smart and Flexible School Bell Management System**

A browser-based application designed to automate school bells, manage daily timetables, and handle unexpected changes to the school schedule.

Developed as part of a school digitalization initiative, this system helps school administrators manage bell timings efficiently without repeatedly adjusting the schedule manually.

## ✨ Key Features

### 1. Automated School Bell Scheduling

- Automatically plays bell sounds at scheduled times.
- Supports a daily timetable with eight teaching periods.
- Includes interval, register marking, and school departure events.
- Displays upcoming bell events and their scheduled times.
- Allows administrators to start and stop the bell system.

### 2. Prayer Ran Late — Automatic Timetable Recalculation

One of the main features of this system is its ability to adjust the school timetable when morning prayer or assembly finishes later than expected.

Normally, a delay in morning activities affects the entire school timetable. Manually changing every period is time-consuming and may result in errors.

The **Prayer Ran Late** feature solves this problem by automatically recalculating the timetable.

**How it works:**

1. Click the **Prayer Ran Late** button.
2. Enter the new starting time of Period 1.
3. Confirm the school's departure time.
4. Click **Confirm & Recalculate**.
5. The system automatically adjusts the eight teaching periods.

**Important characteristics:**

- Keeps the selected school departure time unchanged.
- Maintains the configured interval duration.
- Maintains the register-marking duration.
- Distributes the available teaching time equally among eight periods.
- Automatically updates the daily timetable and upcoming bell times.
- Reduces the need for manual timetable corrections.

**Example:**

Suppose the school normally starts Period 1 at 7:30 AM, but morning prayer finishes late and classes can only begin at 8:00 AM.

Instead of extending the school day, the administrator can enter 8:00 AM as the new starting time.

The system recalculates the teaching periods to fit within the remaining school hours while preserving the interval and departure time.

This allows the school to maintain an organized schedule even when morning activities are delayed.

### 3. Flexible Timetable Adjustments

The system also supports smaller timetable changes during the school day.

Administrators can:

- Move remaining bells 5 minutes earlier.
- Delay remaining bells by 5 or 10 minutes.
- Enter a custom time adjustment.
- Restore the normal timetable when required.
- Continue the timetable when the school day has already started.

Unlike the Prayer Ran Late feature, these adjustments are intended for minor changes to the remaining schedule.

### 4. Customizable School Timetable

Administrators can configure the school's daily schedule, including:

- Period 1 starting time.
- Duration of individual teaching periods.
- Interval duration.
- Register-marking duration.
- School departure time.
- Automatic adjustment of period durations when morning activities are delayed.

The timetable is displayed in an organized format for easy review.

### 5. Real-Time Clock and Bell Countdown

The main dashboard provides live information about the school day.

It displays:

- Current date and time.
- Current bell-system status.
- Next scheduled bell time.
- Description of the upcoming bell.
- Remaining time until the next bell.

This allows school staff to monitor the schedule without manually checking the timetable.

### 6. Daily Bell Timeline

The application displays the scheduled bell events for the day.

Events are visually distinguished according to their status, making it easier to identify completed events and upcoming bells.

### 7. Custom Bell Audio Management

Administrators can configure different audio files for bell events.

Features include:

- Uploading custom audio files.
- Assigning sounds to individual bell events.
- Using built-in chimes when custom audio is unavailable.
- Adjusting playback volume.
- Stopping currently playing audio.

This allows the school to use different sounds for different activities.

### 8. Virtual Clock and Date Adjustment

The system includes a virtual clock that allows administrators to enter a custom date and time.

This is useful for:

- Testing bell schedules.
- Checking whether timetable adjustments work correctly.
- Simulating different times of the school day.
- Using a manually selected time when the computer clock is incorrect.

The virtual clock continues running after it is applied.

Administrators can select **Use PC Clock** to return to the computer's normal time.

### 9. Light and Dark Modes

The application supports two interface themes:

- **Light Mode:** Suitable for normal daytime use.
- **Dark Mode:** Provides an alternative appearance for different working environments.

The interface is designed to be simple and easy for school staff to operate.

### 10. Bell System Controls

The dashboard provides controls to:

- Start the automated bell system.
- Stop the automated bell system.
- Stop currently playing audio.
- Open timetable settings.
- Adjust the current day's schedule.

### 11. Browser-Based Operation

The system runs directly in a modern web browser.

It does not require a separate backend server or database for its core scheduling functions.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Interface design and responsive layout |
| JavaScript | Scheduling and timetable calculations |
| Web Audio API | Bell sound generation and playback |
| Browser Storage | Storing supported application settings and audio data |

## 📁 Project Structure

```text
digital_bell_system/
├── audios/
├── digital-bell-system.html
└── README.md
```

## 🚀 Installation and Setup

### Step 1: Download the Project

Clone the repository:

```bash
git clone https://github.com/Jegathayini/digital_bell_system.git
```

Alternatively, download the repository as a ZIP file.

### Step 2: Open the Application

Open `digital-bell-system.html` in Google Chrome, Microsoft Edge, or another modern browser.

### Step 3: Configure the Timetable

Open **View Timetable** and configure the school's schedule.

### Step 4: Configure Audio

Open **Audio Files** to assign custom sounds if required.

### Step 5: Start the System

Click **Start Bell System** to enable automatic bell scheduling.

Ensure that the browser has permission to play audio.

## ⚠️ Important Operational Requirements

For reliable school operation:

- Keep the computer powered on and awake during school hours.
- Keep the application open while the bell system is running.
- Ensure speakers are properly connected.
- Check the computer and application volume.
- Verify the timetable before the school day begins.
- Maintain a manual backup procedure in case of technical problems.

**Important:** The application cannot guarantee bell playback while the computer is sleeping, shut down, or the browser is closed.

## 🎯 Project Objectives

The Digital Bell System was developed to:

- Reduce manual bell operation.
- Improve consistency in school scheduling.
- Simplify timetable adjustments.
- Handle unexpected delays in morning activities.
- Provide a user-friendly system for school administrators.
- Support the digital transformation of school operations.

## 🔮 Future Improvements

Possible future enhancements include:

- Background scheduling independent of the browser.
- Automatic startup with the school computer.
- Timetable backup and restoration.
- Bell activity reports.
- Improved recovery after unexpected shutdowns.
- Integration with other school management systems.

## 👩‍💻 Developed By

**Jegathayini Thiruchchelvam**

GitHub: [@Jegathayini](https://github.com/Jegathayini)

Project Repository: [Digital Bell System](https://github.com/Jegathayini/digital_bell_system)

---

**Developed to support smarter, simpler, and more efficient school administration.**
