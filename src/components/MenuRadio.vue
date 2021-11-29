<template>
  <div class="temp">
    <p>Choose one of the avalaible timeslot :</p>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">12:00</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">12:30</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">13:00</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">13:30</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">14:00</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">14:30</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">15:00</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">15:30</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">16:00</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">18:00</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">18:30</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">19:00</label>
    </div>
    <div>
      <input type="radio" id="rdv" name="Hour" value="rdv" />
      <label for="rdv">19:30</label>
    </div>
  </div>

  <p> Info about available timeslots </p>
  
</template>

<script>
export default {
  name: "MenuRadio",
  props: {
    msg: String,
  },
};
</script>

<style>
</style>