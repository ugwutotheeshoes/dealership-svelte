
<script>
    import cars from "./store/cars";
</script>

<div id="carPage">
    { #each $cars as car }
            <p>{car.make} {car.model}</p>
            <p>{car.year}</p>
            <hr />
    { /each }
</div>