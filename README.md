# Travel Buddy
Build a travel buddy finder
Travel buddy is a web application that helps you find a buddy, ready to join you in your next venture!!!

# Main Features
<ul>
<li>Geolocation to find other people in your travel destination </li>
<li>Ratings for other travel buddies </li>
<li>Personal profiles to connect with old friends, new friends, and more! </li>
</ul>

# Web Application Tech Stack
<ul>
<li>FrontEnd: React</li>
<li>BackEnd: Node</li>
<li>Database: mySQL </li>
</ul>

# Models
<ul>
  <li>User 
    <ul>
       <li>ID</li>
       <li>Name</li>
       <li>Email</li>
       <li>Ratings: Ratings[]</li>
       <li>DOB</li>
       <li>Gender</li>
       <li>Location (Geospacial data)</li>
       <li>Friends: User[]</li>
       <li>Favorited_destinations: Destination[]</li>
    </ul>
  </li>
  <li>Destination
    <ul>
      <li>Location (Geospacial data)</li>
      <li>Name</li>
    </ul>
  </li>
  <li>Ratings
    <ul>
      <li>Rater</li>
      <li>Rated</li>
      <li>Score</li>
      <li>Comment</li>
    </ul>
  </li>
</ul>

# API

# UI
