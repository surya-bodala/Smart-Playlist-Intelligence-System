# Smart-Playlist-Intelligence-System
Here’s a clean and professional **README.md** for your project:

---

# 🎵 Smart Playlist Intelligence System

## 📌 Project Overview

The **Smart Playlist Intelligence System** is a simple Python-based console application that analyzes a playlist based on song durations.

It evaluates:

* Total playlist duration
* Number of songs
* Minimum and maximum durations
* Repetitive durations
* Overall balance of the playlist

Based on these factors, it categorizes the playlist and provides recommendations for improvement.

---

## 🚀 Features

* ✅ Accepts user input for number of songs
* ✅ Validates song durations (must be greater than 0)
* ✅ Calculates:

  * Total duration
  * Song count
  * Minimum & maximum duration
  * Duration variation
* ✅ Detects repetitive song durations
* ✅ Classifies playlist into categories:

  * Too Short Playlist
  * Too Long Playlist
  * Repetitive Playlist
  * Balanced Playlist
  * Irregular Playlist
* ✅ Provides improvement suggestions

---

## 🛠️ How It Works

1. User enters the number of songs.
2. User enters duration (in seconds) for each song.
3. System validates inputs:

   * If any duration ≤ 0 → Invalid Playlist.
4. If valid:

   * Performs analysis.
   * Categorizes playlist.
   * Displays recommendation.

---

## 📊 Playlist Classification Logic

| Condition                   | Category            | Recommendation                |
| --------------------------- | ------------------- | ----------------------------- |
| Total duration < 300 sec    | Too Short Playlist  | Add more songs                |
| Total duration > 3600 sec   | Too Long Playlist   | Split into multiple playlists |
| Repeated durations found    | Repetitive Playlist | Add more variety              |
| Duration variation > 30 sec | Balanced Playlist   | Good listening session        |
| Otherwise                   | Irregular Playlist  | Adjust durations              |

---

## ▶️ How to Run

1. Make sure Python is installed (Python 3.x recommended).
2. Save the file as:

```
smart_playlist.py
```

3. Run the program:

```
python smart_playlist.py
```

---

## 💻 Example Run

```
Enter number of songs that you want to insert into your playlist: 3
Enter duration in seconds: 200
Enter duration in seconds: 180
Enter duration in seconds: 220

Total Duration of PlayList: 600 seconds
Songs count in playList: 3
Category of PlayList: Balanced Playlist
Recommendation : Good listening session
```

---

## ⚠️ Input Validation

If any duration is less than or equal to 0:

```
Invalid Playlist: Contains invalid duration (<= 0)
```

---

## 📚 Technologies Used

* Python 3
* Basic loops and conditionals
* List operations
* Nested loops for repetition detection

---

## 🔮 Possible Future Improvements

* Optimize repetition detection using sets
* Add average duration calculation
* Convert into a GUI application
* Export playlist report to a file
* Integrate with music APIs

---

## 👨‍💻 Author

Developed as a Python logic-building project to practice:

* Conditional logic
* Loop structures
* Data validation
* Basic algorithm design
