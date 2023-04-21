<template>
  <button
    class="btn btn-primary"
    data-bs-target="#exampleModalToggle3"
    data-bs-toggle="modal"
    data-bs-dismiss="modal"
  ></button>

  <!-- Modal -->
  <div
    class="modal fade"
    id="exampleModal"
    tabindex="-1"
    aria-labelledby="exampleModalLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog">
      <div
        class="modal-content"
        style="
          width: 114%;
          height: 264.13px;
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
              color: #989fa1;
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
            <div
              style="
                margin-left: 9%;
                width: 82%;
                margin-top: 1%;
                display: flex;
                align-items: center;
                text-align: center;
              "
            >
              <p
                style="
                  font-style: normal;
                  font-weight: 300;
                  font-size: 16px;
                  line-height: 150%;
                "
              >
                We have sent you a letter with a password recovery link. Please
                check your e-mail.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style></style>
