# unit-4-game-

var random_result;
var lost;
var win;


for (var i=0; i < 4; i++){
   
    var random = Math.floor(Math.random() × 12);
   
    var crystal = $("<div>");
        crystal. attr ({
                "class"; 'crystal',
                "data-random"
        });
        
    
    crystal.append(crystal);

        
}

//pseudo coding 
// a game with 4 crystals and a random result
// every crystal needs to have a random number 
// a new random number should generate every single time win or loss
// to those 4 crystals
// when clicking any crystal, it should add with the previous
// until it equals the total score 
// if it is greater than the random result, then a loss is happens
// if it is equal, then you win the game 
