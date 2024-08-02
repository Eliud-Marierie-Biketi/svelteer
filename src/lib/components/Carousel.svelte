<script>
    import image1 from '$lib/images/pexels-truthvisual-4063607.jpg'
    import image2 from '$lib/images/pexels-godisable-jacob-226636-977539.jpg';
    import image3 from '$lib/images/pexels-nashon-otieno-461418010-15638645.jpg';
    import image4 from '$lib/images/pexels-ottunthe3rd-11440539.jpg';
    import image5 from '$lib/images/pexels-safari-consoler-3290243-11211022.jpg';
    import image6 from '$lib/images/pexels-vera-ofure-70980050-8463413.jpg';
    import image7 from '$lib/images/pexels-cottonbro-5894872.jpg';
</script>

<style>
    .carousel {
        display: flex; /* Use flexbox to layout the carousel items */
        justify-content: space-between; /* Space items evenly */
        overflow: hidden; /* Hide any overflowed content */
        width: 100%; /* Adjust the width of the carousel */
        padding: 0 10px; /* Optional: Add padding to prevent images from touching the edges */
    }

    .carousel-item {
        flex: 1; /* Allow items to grow and shrink equally */
        display: flex; /* Use flexbox for image alignment */
        justify-content: center; /* Center the image within the item */
    }

    .carousel-item img {
        max-width: 150px; /* Ensures the image does not exceed its container width */
        height: auto; /* Maintains the aspect ratio */
        border-radius: 0.5rem; /* Optional: Adds rounded corners to the images */
    }
</style>

<div class="carousel carousel-center rounded-box">
    <div class="carousel-item">
        <img src={image1} alt="Close-up of cotton plants in a field" />
    </div>
    <div class="carousel-item">
        <img src={image2} alt="Man in a casual outfit working on a laptop" />
    </div>
    <div class="carousel-item">
        <img src={image3} alt="Group of people in a meeting around a table" />
    </div>
    <div class="carousel-item">
        <img src={image4} alt="A scenic landscape with mountains and trees" />
    </div>
    <div class="carousel-item">
        <img src={image5} alt="A scenic landscape with mountains and trees" />
    </div>
    <div class="carousel-item">
        <img src={image6} alt="Woman standing by a large window with a city view" />
    </div>
    <div class="carousel-item">
        <img src={image7} alt="Close-up of cotton plants in a field" />
    </div>
</div>