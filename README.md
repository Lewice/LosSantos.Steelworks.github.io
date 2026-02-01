<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Los Santos Steel Works</title>
  <script src="https://code.jquery.com/jquery-3.4.1.js" integrity="sha256-WpOohJOqMqqyKL9FccASB9O0KwACQJpFTUBLTYOVvVU=" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <link rel="stylesheet" href="styles.css">
  <script src="script.js"></script>
</head>
<body>
  <div class="history-button">
    <button type="button" id="historyBtn" title="Order History"><i class="fas fa-history"></i></button>
  </div>
  <h2>Los Santos Steel Works</h2>
  <form id="menuForm">
    <h3>Service Items</h3>
    <label>
      <input type="checkbox" class="menu-item" data-price="500"> spark plug - 500$
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="500">  brakepad replacement - 500$
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="500"> engine oil - 500$
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="500"> air filter - 500
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="500"> clutch replacement - 500
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="500"> extras kit - 500
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="500"> respray kit - 500
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="500"> tire replacement - 500
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> performance parts - 1,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> cosmetic parts - 1,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> repair kits - 1,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="750"> ceramic brakes - 750
      <input type="number" class="quantity" value="1" min="1">
    </label>    
    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> nitrous install kit - 1,000
      <input type="number" class="quantity" value="1" min="1">
    </label>	
    <label>
      <input type="checkbox" class="menu-item" data-price="750"> nitrous bottle - 750
      <input type="number" class="quantity" value="1" min="1">
    </label>		
    <label>
      <input type="checkbox" class="menu-item" data-price="100"> cleaning kit - 100 
      <input type="number" class="quantity" value="1" min="1">
    </label>		
		
    <label>
      <input type="checkbox" class="menu-item" data-price="750"> tire smoke kit 750
      <input type="number" class="quantity" value="1" min="1">
    </label>	
    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> bulletproof tires - 1,000
      <input type="number" class="quantity" value="1" min="1">
    </label>		
    <label>
      <input type="checkbox" class="menu-item" data-price="750"> drift tuning kit - 750
      <input type="number" class="quantity" value="1" min="1">
    </label>
	
	<h3>Tires</h3>


    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> slick tires - 1,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> semi slick tires - 1,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> off road tires - 1,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
	
	<h3>Misc</h3>	
	
    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> lighting controller - 1,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="60"> 9mm Bullet - $60
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="80"> 5.56 Bullet - $80
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="60"> .45 Acp Bullet - $60
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="60"> 10mm Bullet - $60
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="60"> .50ae Bullet - $60
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="60"> Shotgun Ammo - $60
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="80"> 7.62 Bullet - $80
      <input type="number" class="quantity" value="1" min="1">
    </label>

	
	<h3>EV Parts</h3>	
    <label>
      <input type="checkbox" class="menu-item" data-price="750"> EV Motor - 750
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="750"> EV Coolant - 750
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="750"> EV Battery - 750
      <input type="number" class="quantity" value="1" min="1">
    </label>

	
	<h3>Engine</h3>	
	
	

    <label>
      <input type="checkbox" class="menu-item" data-price="10000"> v6 engine - 10,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="10000"> v8 engine - 10,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="10000"> v12 engine - 10,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> turbo charger - 1,000
      <input type="number" class="quantity" value="1" min="1">
    </label>
	
	<h3>Suspension</h3>	
	
	
    <label>
      <input type="checkbox" class="menu-item" data-price="500"> suspension parts - 500
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <h3>Transmission Upgrades</h3>
    <label>
      <input type="checkbox" class="menu-item" data-price="1000"> stancer kit - 1000
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="1500"> awd drivetrain - 1,500
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="1500"> rwd drivetrain - 1,500
      <input type="number" class="quantity" value="1" min="1">
    </label>
    <label>
      <input type="checkbox" class="menu-item" data-price="1500"> fwd drivetrain - 1,500
      <input type="number" class="quantity" value="1" min="1">
    </label>

    <div style="margin-bottom: 30px;"></div>
    <label for="discount">Select Discount:</label>
    <select id="discount">
      <option value="0">No Discount</option>
    </select>
    <div style="margin-bottom: 30px;"></div>
    <label for="employeeName">Customer Name:</label>
    <input type="text" id="employeeName" required>
    <div style="margin-bottom: 30px;"></div>
    <p>Total: $<span id="total"></span></p>
    <div style="margin-bottom: 30px;"></div>
    <div class="button-group">
      <button type="button" id="calculateBtn" onclick="calculateTotals()">Calculate</button>
      <button type="button" onclick="SubForm()">Submit</button>
      <button type="button" onclick="resetForm()">Reset</button>
    </div>
  </form>
  <div id="historyModal" class="modal">
    <div class="modal-content">
      <span class="close">×</span>
      <h3>Order History</h3>
      <div id="historyContent"></div>
    </div>
  </div>
</body>
</html>




