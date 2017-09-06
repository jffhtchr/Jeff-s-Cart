var cart = [{bananas: "2"}, {plums: "5"}];

function getCart() {
 return cart;
}

function setCart(c) {
  cart = c;
  return cart;
}

function addToCart(item) {
  var itemName = item;
  var itemConstructor = new Object();
  itemConstructor[itemName] = Math.floor(Math.random()*50);
  cart.push(itemConstructor)
  console.log(`${itemName} has been added to your cart.`);
  return cart;
}

function viewCart() {
  var text = 'In your cart, you have '
  if(cart.length === 0){
    return `Your shopping cart is empty.`}
  for(var item = 0; item<cart.length; item++ ){
    if(item === cart[cart.length-1]) {
      text +=  ' and ' + Object.keys(cart[item]) + " at $" + Object.values(cart[item]) + '.'
    }else{
      text += Object.keys(cart[item]) + " at $" + Object.values(cart[item]) + ', ' 
     } }return text
}

 viewCart();
