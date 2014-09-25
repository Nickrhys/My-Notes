5 Steps of good protocol Javascript testing

STEP 1
======

describe({
	// create the closing brackets to create the description
});  

STEP 2
======

describe('', function (){
	// add the quotation marks, comma, function and parenthesis
});  

STEP 3
======

describe('', function (){

	it({
	 	// create the closing brackets to create the test
	});

});  

STEP 4
======

describe('', function (){

	it('', function(){
	 	// add the quitation marks, comma, function and parenthesis for the test
	});

}); 

STEP 5
====== 

describe('', function (){

	it('', function(){
		expect(class.test).to(outcome); // add your expectations and outcome for the test. 
	});

}); 