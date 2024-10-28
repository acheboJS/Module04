function calculateTip(){
	var amount;
	var quality;
	
	
	while (true){
		var amountInput = prompt("Please enter an amount between 5 and 500");
		amount = Number(amountInput);
		
		if (amount >= 5 && amount <= 500){
		 break;
		} else {
			alert("Please enter an amount between 5 and 500");
		}
	}
	
	
	while(true){
		quality = prompt("How was the service? great, ok, or poor");
		
		if (quality === 'great' || quality === 'ok' || quality === 'poor'){
		 break;
		} else {
			alert("Please enter either 'great', 'ok', or 'poor'");
		}
	}
	
	var tip;
	if (quality === 'great') {
		tip = amount * 0.20;
	} else if (quality === 'ok'){
		tip = amount * 0.15;
	} else if (quality === 'poor'){
		tip = amount * 0.10;
	}

	alert("For a service amount of $" + amount + " with " + quality + " service, the tip is $" + tip + ".");
}
calculateTip();
