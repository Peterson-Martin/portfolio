# portfolio
my personal portfolio
# portfolio
my personal portfolio
<!DOCTYPE html>
<html>
<body>

<p id="demo"></p>

<script>
function address(city, state, zip) {
    this.cityName = city;
    this.stateName = state;
    this.zip = zip;
}
address.prototype.name = function() {
    return this.cityName + " " + this.lastState
};

var myAddress = new address("Little Rock", "Arkansas", 72221);
document.getElementById("demo").innerHTML =
"My address is " + my.address(); 
</script>

</body>
</html>
