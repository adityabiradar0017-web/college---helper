<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>College Helper - One Page</title>
</head>
<body>
  <h1>📘 College Helper</h1>
  <p>Welcome! Your one-stop solution for attendance, notes, and exam updates.</p>

  <!-- Navigation Menu -->
  <hr>
  <p>
    <a href="#attendance">Attendance</a> | 
    <a href="#notes">Notes</a> | 
    <a href="#timetable">Timetable</a> | 
    <a href="#about">About</a>
  </p>
  <hr>

  <!-- Attendance Section -->
  <h2 id="attendance">📊 Attendance Calculator</h2>
  <form>
    <label>Total Lectures: </label><input type="number"><br><br>
    <label>Attended Lectures: </label><input type="number"><br><br>
    <input type="submit" value="Check Attendance">
  </form>
  <p><b>Note:</b> Calculate manually → (Attended ÷ Total) × 100</p>
  <hr>

  <!-- Notes Section -->
  <h2 id="notes">📚 Notes Section</h2>
  <ul>
    <li><a href="#">Mathematics Notes (PDF)</a></li>
    <li><a href="#">Physics Notes (PDF)</a></li>
    <li><a href="#">Computer Science Notes (PDF)</a></li>
  </ul>
  <hr>

  <!-- Timetable Section -->
  <h2 id="timetable">📝 Exam Timetable</h2>
  <table border="1" cellpadding="5">
    <tr>
      <th>Subject</th>
      <th>Date</th>
      <th>Time</th>
    </tr>
    <tr>
      <td>Mathematics</td>
      <td>20-Nov-2025</td>
      <td>10:00 AM</td>
    </tr>
    <tr>
      <td>Physics</td>
      <td>22-Nov-2025</td>
      <td>2:00 PM</td>
    </tr>
    <tr>
      <td>Computer Science</td>
      <td>25-Nov-2025</td>
      <td>10:00 AM</td>
    </tr>
  </table>
  <hr>

  <!-- About Section -->
  <h2 id="about">ℹ️ About College Helper</h2>
  <p>This website is created to help students manage their attendance, access notes, and stay updated with exam timetables.</p>
  <ul>
    <li>Attendance Calculator</li>
    <li>Notes Section</li>
    <li>Exam Timetable</li>
    <li>Important Updates</li>
  </ul>
  <p>Created by: <b>AAditya Biradar</b></p>
</body>
</html>
