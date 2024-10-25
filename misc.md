---
layout: page
title: Misc
---

<style>
/* Container for the entire page */
.misc-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 20px;
}

/* Individual section styling */
.misc-section {
    display: flex;
    flex-direction: row;
    width: 30%; /* Adjust width to fit three sections horizontally */
    background-color: #f9f9f9;
    padding: 10px;
    border-radius: 8px;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.1);
}

/* Styling for the image */
.misc-image {
    max-width: 100px;
    margin-right: 15px;
    border-radius: 5px;
}

/* Styling for the text */
.misc-text {
    font-size: 0.9em;
    line-height: 1.4em;
}
</style>

<div class="misc-container">
    <!-- Section 1 -->
    <div class="misc-section">
        <img class="misc-image" src="static/img/marathon.PNG" alt="Photo 1">
        <div class="misc-text">
            <h3>Section 1 Title</h3>
            <p>
                My first New York City Full Marathon.
            </p>
        </div>
    </div>

    <!-- Section 2 -->
    <div class="misc-section">
        <img class="misc-image" src="path/to/photo2.jpg" alt="Photo 2">
        <div class="misc-text">
            <h3>Section 2 Title</h3>
            <p>
                Description or text content for the second section. This is a great place to provide additional information.
            </p>
        </div>
    </div>

    <!-- Section 3 -->
    <div class="misc-section">
        <img class="misc-image" src="path/to/photo3.jpg" alt="Photo 3">
        <div class="misc-text">
            <h3>Section 3 Title</h3>
            <p>
                Description or text content for the third section. Feel free to modify this text to fit your needs.
            </p>
        </div>
    </div>
</div>
