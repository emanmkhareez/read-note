# chart:way to display data this way make understand data quickly 

to use chart in javascript must download  Chart.js.

To draw a line chart-->create a canvas element in our HTM.

Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:

<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>