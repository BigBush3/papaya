<template>
  <div class="modal-dialog modal-lg">
    <div
      style="width: 120%; height: 100%; border-radius: 67px; flex-wrap: wrap"
      class="modal-content"
    >
      <div class="modal-header">
        <h5
          style="font-size: 18px; margin-left: 5%; margin-top: 3%"
          class="modal-title"
          id="exampleModalLabel"
        >
          Back
        </h5>
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="modal"
          aria-label="Закрыть"
          style="margin-right: 3%; margin-top: 3%"
        ></button>
      </div>
      <div style="left: 0" class="modal-body">
        <div
          class="container"
          style="display: flex; justify-content: center; align-items: center"
        >
          <form>
            <div class="mb-3" style="display: flex; justify-content: center">
              <h1
                style="
                  font-style: normal;
                  font-weight: 400;
                  font-size: 36px;
                  line-height: 41px;

                  color: #1d2024;
                "
              >
                Company Registration Form
              </h1>
            </div>
            <div style="display: flex; justify-content: center">
              <p
                style="
                  font-style: normal;
                  font-weight: 300;
                  font-size: 16px;
                  line-height: 120%;
                  /* or 19px */

                  display: flex;
                  align-items: center;

                  color: #38484f;
                "
              >
                Please complete the form
              </p>
            </div>

            <div class="accordion" id="accordionExample">
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button
                    class="accordion-button"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#collapseOne"
                    aria-expanded="true"
                    aria-controls="collapseOne"
                  >
                    Accordion Item #1
                  </button>
                </h2>
                <div
                  id="collapseOne"
                  class="accordion-collapse collapse show"
                  data-bs-parent="#accordionExample"
                  style="width: 902px; max-width: 100%; height: 270px"
                >
                  <div class="accordion-body">
                    <div>
                      <p
                        style="
                          font-style: normal;
                          font-weight: 500;
                          font-size: 14px;
                          line-height: 120%;
                          /* identical to box height, or 17px */

                          display: flex;
                          align-items: center;
                          text-transform: uppercase;

                          color: #1d2024;
                        "
                      >
                        About Company
                      </p>
                    </div>
                    <div style="display: flex; margin-top: 3%">
                      <div>
                        <label
                          style="
                            font-size: 19px;
                            margin-left: %;
                            font-style: normal;
                            font-weight: 500;
                            font-size: 14px;
                            line-height: 120%;
                            /* identical to box height, or 17px */

                            display: flex;
                            align-items: center;

                            color: #1d2024;
                          "
                          for="exampleInputPassword1"
                          class="form-label"
                          >Company Name</label
                        >

                        <input
                          style="
                            width: 200%;
                            height: 56px;
                            border-radius: 13px;
                            background: #f1f5f8;
                          "
                          type="password"
                          class="form-control"
                          id="exampleInputPassword1"
                          placeholder="Please enter password"
                        />
                      </div>
                      <div style="margin-left: 25%;margin-top: 3%;">
                        <div
                          class="dropdown"
                          style=" "
                        >
                          <button
                            class="btn btn-secondary dropdown-toggle"
                            type="button"
                            id="dropdownMenuButton1"
                            data-bs-toggle="dropdown"
                            aria-expanded="false"
                            style="
                              background: #f1f5f8;
                              border-radius: 10px;
                              width: 200%;
                              height: 56px;

                            "
                          >
                            <p
                              style="
                                font-style: normal;
                                font-weight: 300;
                                font-size: 14px;
                                line-height: 200%;
                                /* identical to box height, or 28px */

                                display: flex;
                                align-items: center;

                                color: #727778;
                              "
                            >
                              Please choose from the list below
                            </p>
                          </button>
                          <ul
                            class="dropdown-menu"
                            aria-labelledby="dropdownMenuButton1"
                          >
                            <li>
                              <a class="dropdown-item" href="#">Действие</a>
                            </li>
                          </ul>
                        </div>
                      </div>
                    </div>

                    <div
                      style="
                        display: flex;
                        justify-content: center;
                        margin-top: 4%;
                      "
                    >
                      <button
                        style="
                          background: #ffffff;
                          border: 1px solid #1d2024;
                          border-radius: 35px;
                          width: 30%;
                        "
                      >
                        <p
                          style="
                            display: flex;
                            justify-content: center;
                            margin-top: 2%;
                            font-style: normal;
                            font-weight: 500;
                            font-size: 14px;
                            line-height: 200%;
                            color: #1D2024;;
                          "
                        >
                          Save
                        </p>
                      </button>
                    </div>
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button
                    class="accordion-button collapsed"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#collapseTwo"
                    aria-expanded="false"
                    aria-controls="collapseTwo"
                  >
                    Accordion Item #2
                  </button>
                </h2>
                <div
                  id="collapseTwo"
                  class="accordion-collapse collapse"
                  data-bs-parent="#accordionExample"
                >
                  <div class="accordion-body">
                    <strong>This is the second item's accordion body.</strong>
                    It is hidden by default, until the collapse plugin adds the
                    appropriate classes that we use to style each element. These
                    classes control the overall appearance, as well as the
                    showing and hiding via CSS transitions. You can modify any
                    of this with custom CSS or overriding our default variables.
                    It's also worth noting that just about any HTML can go
                    within the <code>.accordion-body</code>, though the
                    transition does limit overflow.
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button
                    class="accordion-button collapsed"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#collapseThree"
                    aria-expanded="false"
                    aria-controls="collapseThree"
                  >
                    Accordion Item #3
                  </button>
                </h2>
                <div
                  id="collapseThree"
                  class="accordion-collapse collapse"
                  data-bs-parent="#accordionExample"
                >
                  <div class="accordion-body">
                    <strong>This is the third item's accordion body.</strong> It
                    is hidden by default, until the collapse plugin adds the
                    appropriate classes that we use to style each element. These
                    classes control the overall appearance, as well as the
                    showing and hiding via CSS transitions. You can modify any
                    of this with custom CSS or overriding our default variables.
                    It's also worth noting that just about any HTML can go
                    within the <code>.accordion-body</code>, though the
                    transition does limit overflow.
                  </div>
                </div>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<style></style>

<script></script>
