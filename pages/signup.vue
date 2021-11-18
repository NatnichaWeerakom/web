<template>
  <div class="box">
    <v-form>
      <p>Sign up your bank account</p>
      <v-text-field
        label="Your Name"
        outlined
        dense
        style="padding: 0px 20px 0px 20px;"
      />
      <v-text-field
        label="Bank Account"
        outlined
        dense
        style="padding: 0px 20px 0px 20px;"
      />
      <v-text-field
        label="Moblie Phone Number"
        outlined
        dense
        style="padding: 0px 20px 0px 20px;"
      />
      <v-text-field
        label="Email"
        outlined
        dense
        style="padding: 0px 20px 0px 20px;"
      />
      <v-text-field
        label="Password"
        outlined
        dense
        style="padding: 0px 20px 10px 20px;"
        append-icon="mdi-eye"
      />
      <div class="mess">
        Use 6 characters with a mix of numbers and letters
      </div>
      <v-checkbox
        label="By signning up, you agree to bank's term of User & Privacy Policy."
        color="blue darken-3"
      />
      <v-row>
        <v-col class="d-flex justify-center ">
          <v-btn class="btn1">
            <span class="txt1">Sign Up</span>
          </v-btn>
          <p> or </p>
          <v-btn
            class="ma-2"
            outlined
            color="indigo"
          >
            CANCLE
          </v-btn>
        </v-col>
      </v-row>
      <div class="signed">
        Already signed up? <a href="#" class="log">Log in</a>
      </div>
    </v-form>
  </div>
</template>

<style>

.box{
  background-color: rgb(255, 255, 255);
  border-radius: 10px;
  margin: 20px;
  font-family: sans-serif;
}
p{
  color: rgb(56, 142, 255);
  padding: 20px;

}
.mess{
  color: rgb(56, 142, 255);
  font-family: sans-serif;
}
.signed{
  color: rgb(56, 142, 255);
  font-family: sans-serif;
}
.v-text-field--outlined fieldset{
  color: #27272c !important;
}
.v-text-field--outlined label{
  color: #313136b0 !important;
}
.v-checkbox--label{
  color: #27272c !important;
}
.btn1{
  background: linear-gradient(to bottom,#ffeb3b,#ffc107);
  margin-top: 7px;
}
.txt1{
  color: black;
  font-family: sans-serif;
}
.log{
  color: cornflowerblue;
}

</style>
