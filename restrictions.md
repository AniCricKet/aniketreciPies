<head>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
      body {
        font-family: 'Poppins', sans-serif;
      }
      .dropdown {
        position: relative;
        display: inline-block;
      }
      .dropdown-button {
        background-color: black;
        color: white;
        padding: 16px;
        border: none;
        cursor: pointer;
      }
      .dropdown-content {
        display: none;
        position: absolute;
        width: 200px;
        background-color: #f9f9f9;
        min-width: 160px;
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
        z-index: 1;
      }
      .dropdown-content input[type="checkbox"] {
        margin-right: 10px;
      }
      .dropdown:hover .dropdown-content {
        display: block;
      }
    </style>
  </head>
  <body>
    <div class="dropdown">
      <button class="dropdown-button">Select Options</button>
      <form>
        <fieldset>
          <legend id="dietary-restrictions-label"></legend>
          <div class="dropdown-content" aria-labelledby="dietary-restrictions-label">
            <input type="checkbox" id="vegan" name="dietary-restrictions" value="vegan">
            <label for="vegan">Vegan</label><br>
            <input type="checkbox" id="vegetarian" name="dietary-restrictions" value="vegetarian">
            <label for="vegetarian">Vegetarian</label><br>
            <input type="checkbox" id="gluten-free" name="dietary-restrictions" value="gluten-free">
            <label for="gluten-free">Gluten Free</label><br>
            <input type="checkbox" id="lactose-intolerant" name="dietary-restrictions" value="lactose-intolerant">
            <label for="lactose-intolerant">Lactose Intolerant</label><br>
            <input type="checkbox" id="no-fish" name="dietary-restrictions" value="no-fish">
            <label for="no-fish">No Fish</label><br>
            <input type="checkbox" id="nut-free" name="dietary-restrictions" value="nut-free">
            <label for="nut-free">Nut Free</label><br>
            <input type="button" value="Save Preferences">
          </div>
          <div id="search_page">
          <button id="searchButton">Search</button>
        <div>
            
        <br>
        <div id="results">
  <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
  </body>
