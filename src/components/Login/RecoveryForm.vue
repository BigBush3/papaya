<template>
  <button
  v-on:click="open"
    type="button"
    class="btn btn-primary"
    data-bs-toggle="modal"
    data-bs-target="#exampleModal3"
    data-bs-dismiss="modal"
  >
    Launch demo modal
  </button>

  <!-- Modal -->
  <div
    class="modal fade"
    id="exampleModal3"
    tabindex="-1"
    aria-labelledby="exampleModalLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog">
      <div
        class="modal-content"
        style="
          width: 114%;
          height: 485.38px;
          background: #ffffff;
          box-shadow: 0px 0px 35px rgba(0, 0, 0, 0.2);
          border-radius: 50px;
        "
      >
        <div class="modal-header">
          <h5
            style="
              margin-top: 2%;
              margin-left: 3%;
              font-style: normal;
              font-weight: 400;
              font-size: 14px;
              line-height: 120%;
              color: #989FA1;
            "
            class="modal-title"
            id="exampleModalLabel"
          >
            Back
          </h5>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
            style="margin-right: 3%; margin-top: 1%"
          ></button>
        </div>
        <div class="modal-body" style="">
          <div class="container">
            <div
              style="
                margin-left: 1%;
                display: flex;
                justify-content: center;
                align-items: center;
              "
            >
              <h1>Password recovery</h1>
            </div>
            <div style="margin-left: 9%; width: 78%; margin-top: 1%">
              <p
                style="
                  font-style: normal;
                  font-weight: 300;
                  font-size: 16px;
                  line-height: 150%;
                "
              >
                Please enter e-mail you specified during registration and we
                will send you a new password.
              </p>
            </div>
            <div class="" style="margin-left: 9%">
              <div class="mb-4">
                <label
                  style="
                    font-size: 19px;
                    color: rgba(29, 32, 36, 1);
                    margin-top: 35px;
                  "
                  for="exampleInputEmail1"
                  class="form-label"
                  >Email</label
                >
                <input
                  style="
                    height: 70px;
                    background: #f1f5f8;
                    border-radius: 13px;

                    width: 93%;
                  "
                  type="email"
                  class="form-control"
                  id="exampleInputEmail1"
                  aria-describedby="emailHelp"
                  placeholder="Please enter your valid e-mail address"
                />
              </div>
            </div>
            <div style="margin-left: 8.5%; display: flex; align-items: center">
              <button
                style="
                  width: 93%;
                  height: 64px;
                  background: #1d2024;
                  border-radius: 35px;
                  color: #ffffff;
                "
              >
                <p
                  style="
                    font-style: normal;
                    font-weight: 500;
                    font-size: 22px;
                    line-height: 200%;
                    margin-top: 2%;
                  "
                >
                  Send
                </p>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import RecoveryText from './RecoveryText.vue'
export default{
  
  data(){return{
        isActive:false
    }},
    methods:{
        open(){this.isActive = true},
        close(){this.isActive = false}
    }, components:{
      RecoveryText
    }
  

}
</script>

<style></style>
