console.log('Loading event');

exports.handler = function(event, context) {
  var restaurant,
      rnd = Math.random();
      
  if (rnd < 0.3) {
      restaurant="Bon Prix";
  } else if (rnd < 0.6) {
      restaurant="Verwaltungskantine";
  } else if (rnd < 0.9) {
      restaurant="Betriebskantine";
  } else {
      restaurant = "Croqueladen";
  }
  
  context.done(null, {"Restaurant":restaurant});
};
