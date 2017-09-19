<template lang="html">
  <div class="">
    <h1> Nightlife Coordination App </h1>
    <h2> What's the Plan for Tonight? </h2>
    <span class="glyphicon glyphicon-glass icon"></span>
    <span class="glyphicon glyphicon-music icon"></span>
    <span class="glyphicon glyphicon-heart icon"></span>

    <div class="input-group input-group-lg search">
      <input class="form-control" type="text" placeholder="Where Will you be tonigh?" aria-describedby="search">
      <span class="search-btn input-group-addon glyphicon glyphicon-search" id="search"></span>
    </div>
  </div>
</template>

<script>
import Yelp from {yelp};
new Yelp({
  consumer_key: 'CMFhpK3uqm-s-BiHBsCBbg',
  consumer_secret: '27z7yNEM2Nzptg02u2mEUoXUKg7JlUCijdXsQfwJDf88Kf8GxovQgMO4G8IEpEd3',
  token: 'token',
  token_secret: 'token-secret',
})
export default {
}
</script>

<style lang="css" scoped>
.search {
  margin-top:60px;

}
.search-btn {
  background-color: #D9853B;
  color: white;
  margin-left: 300px;
}

</style>
