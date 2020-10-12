<template>
  <div class="about">
    <h1>ini buat belajar</h1>
    <div class="columns is-3-desktop">
      <div class="column warna">
        <div class="columns">
          <div class="column">Pendaftaran</div>
        </div>
        <div class="columns">
          <div class="column">
            <div class="section">
              <b-field label="Name">
                <b-input v-model="name"></b-input>
              </b-field>

              <b-field label="Email">
                <b-input type="email"
                placeholder="Email" 
                maxlength="30"
                v-model="email"> </b-input>
              </b-field>

              <b-field label="Password">
                <b-input
                  type="password"
                  placeholder="Password"
                  password-reveal
                  v-model="password"
                >
                </b-input>
              </b-field>
              <b-button type="is-primary">sAVE</b-button>

            </div>
          </div>
        </div>
      </div>
      <div class="column warna" style="max-height: 50px;">
        <div class="columns">
          <h1>login</h1>
          <div class="column">
            <b-field label="Email">
                <b-input type="email"
                placeholder="Email" 
                maxlength="30"
                > </b-input>
              </b-field>

              <b-field label="Password">
                <b-input
                  type="password"
                  placeholder="Password"
                  password-reveal
                
                >
                </b-input>
              </b-field>
              <b-button type="is-primary">login</b-button>

          </div>
        </div>
      </div>
      <div class="column warna">
        <div class="columns">
          <div class="column">
            <h1 class="title is-1">hay , selamat datang disini</h1>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style>

</style>
