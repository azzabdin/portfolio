# portfolio
 this portfolio, is actually ,desplaying my work for the last 3 months of my life,
 between my work,and my kids and this bootcamp, i felt like am drowning at sometimes,
 but i enjoyed each and every one of them, the challenge , the change of thoughts , to be details oriented are all becomes my best friends,
 her you can find some pieces of my codes. for the projects.
 for the giphy:
        for (var i = 0; i < topics.length; i++) {

        // Then dynamicaly generating buttons for each movie in the array.

        var a = $("<button>");
        // Adding a class
        a.addClass("giphy");
        // Adding a data-attribute with a value of the movie at index i
        a.attr("data-name", topics[i]);
        // Providing the button's text with a value of the movie at index i
        a.text(topics[i]);
        // Adding the button to the HTML
        $("#buttons-view").append(a);
    }
}
for the crystal game:
    / All of the same game win-lose logic applies. So the rest remains unchanged.
   // alert("New score: " + counter);

    if (counter === targetNumber) {
   alert("You win!");
   win ++;$("#win").text(win);
   reset ()
    }

    else if (counter >= targetNumber) {
      alert("You lose!!");
      lose++;
      $("#lose").text(lose);
      reset();
      
    }
for the train times:
  var firstTimeConverted = moment(tStart, "HH:mm").subtract(1, "years");
  console.log(firstTimeConverted);


  var currentTime = moment();
  console.log("CURRENT TIME: " + moment(currentTime).format("HH:mm"));


  var diffTime = moment().diff(moment(firstTimeConverted), "minutes");
  console.log("DIFFERENCE IN TIME: " + diffTime);


  var tRemainder = diffTime % tFreq;
  console.log(tRemainder);


  var tMinutesTillTrain = tFreq - tRemainder;
  console.log("MINUTES TILL TRAIN: " + tMinutesTillTrain);


  var nextTrain = moment().add(tMinutesTillTrain, "minutes");
  console.log("ARRIVAL TIME: " + moment(nextTrain).format("HH:mm"));
   and last for the project:
     i was one of 4 very hard working people for this project and we get done to the best to our abilities.
      $.get(getRecipesUrl)
    .then(function (results) {
      console.log(results)
      // display 5 recipes
      var recipes = results.matches
      console.log(recipes)
      // Empty recipe div before displaying list
      $("#recipeResults").empty();
       again i am enjoying the journey hope you are too.