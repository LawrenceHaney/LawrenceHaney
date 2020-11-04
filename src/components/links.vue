<template>
  <div  id="links" class="row p-2 d-flex justify-content-around">
      <div class="flip-card col-4 justify-content-center d-flex flex-column text-center animate__animated animate__fadeIn">
            <div class="flip-card-inner">
              <div class="flip-card-front card-1">
              </div>
              <div class="flip-card-back  card-1">
                <div class="text-light d-flex flex-column darken-bg justify-content-around">

              <h1 class="">D.C.D.R.</h1>
              <p class="">Voting aplication for gaming communities</p>
              <p class="">Vue front end with node.js server that dynamicly pulls users steam library from the steam api</p>
                </div>
              </div>
            </div>
      </div>
      <div class="flip-card col-4 justify-content-center d-flex flex-column text-center animate__animated animate__fadeIn">
            <div class="flip-card-inner">
              <div class="flip-card-front card-2">
              </div>
              <div class="flip-card-back  card-2">
                <div class="text-light d-flex flex-column darken-bg justify-content-around">

              <h1 class="">Inspire</h1>
              <p class="">Elegant landing page for productivity</p>
              <p class="">JavaScript powered frontend that pulls data from several distribuited apis</p>
                </div>
              </div>
            </div>
          </div>
      <div class="flip-card col-4 justify-content-center d-flex flex-column text-center animate__animated animate__fadeIn">
            <div class="flip-card-inner">
              <div class="flip-card-front card-3">
              </div>
              <div class="flip-card-back  card-3">
                <div class="text-light d-flex flex-column darken-bg justify-content-around">

              <h1 class="">Kanban</h1>
              <p class="">Trello inspired productivity tool</p>
              <p class="">Vue.js driven tasktracking application with a node.js backend</p>
                </div>
              </div>
            </div>
          </div>
  </div>
</template>

<script>
export default {
name:"links"
}
</script>

<style>
img{
  object-fit: contain;
}
.flip-card {
  background-color: transparent;
  height:45vh ;
  width: 100%;
  perspective: 1000px;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden; /* Safari */
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: #bbb;
  color: black;
}

.flip-card-back {
  transform: rotateY(180deg);
}

.card-1{
  background-image: url(../assets/Capture.png);
  background-size: cover;

}

.card-2{
  background-image: url(../assets/Inspire.png);
  background-size: cover;

}

.card-3{
  background-image: url(../assets/Kanban.png);
  background-size: cover;

}

.darken-bg{
  background-color: rgba(0, 0, 0, 0.644);
  height: 100%;
}
</style>