<template>
  <div class="container-fluid">
    <!-- Add the image -->
    <img
      src="@/assets/kristine.jpg" 
      alt="Placeholder image" 
      class="image"
    />
      

    <strong>
      <p class="blue-text">
        I'm Kristine, a family-oriented person who values quality time and meaningful connections.
        <br>
        This picture was taken during a fun day out with my family at the mall. From trying out new foods at the food court to sharing laughs in the arcade, these moments are what I treasure most. Family is everything to me, and I believe in creating memories that last a lifetime.
        <br>
        Outside of family time, I enjoy playing badminton with friends, exploring 
    new music genres, and love to help others.
      </p><br>
      Looking forward to sharing more laughter and adventures with you all!
    </strong>
  </div>
</template>

<style scoped>
.container-fluid {
  background-color: rgb(168, 156, 180);
  padding: 200px;
  border-radius: 10px;
  color: #fff;
  display: flex;
  flex-direction: column; /* Ensure flex-direction is column to align vertically */
  justify-content: center;
  align-items: center;
  margin-top: 20px;
}

.image {
  max-width: 150px; /* Control the size of the image */
  border-radius: 50%; /* Example style: circular image */
  margin-bottom: 20px; /* Spacing between the image and the text */
}

.blue-text {
  color: #fff;
}
</style>
