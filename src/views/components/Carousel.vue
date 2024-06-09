<template>
  <div class="card card-carousel overflow-hidden h-100 p-0">
<!--    <div-->
<!--      id="carouselExampleCaptions"-->
<!--      class="carousel slide h-100"-->
<!--      data-bs-ride="carousel"-->
<!--    >-->
<!--&lt;!&ndash;      <div class="carousel-inner border-radius-lg h-100">&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;        <div&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;          class="carousel-item h-100 active"&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;          :style="{&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;            backgroundImage:&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;              'url(' + require('@/assets/img/carousel-1.jpg') + ')',&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;            backgroundSize: 'cover',&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;          }"&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;        >&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;          <div&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;            class="carousel-caption d-none d-md-block bottom-0 text-start start-0 ms-5"&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;          >&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;            <div&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;              class="icon icon-shape icon-sm bg-white text-center border-radius-md mb-3"&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;            >&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;              <i class="ni ni-camera-compact text-dark opacity-10"></i>&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;            </div>&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;            <h5 class="text-white mb-1">Get started with Argon</h5>&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;            <p>&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;              There’s nothing I really wanted to do in life that I wasn’t able&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;              to get good at.&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;            </p>&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;&lt;!&ndash;          </div>&ndash;&gt;&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;&lt;!&ndash;        </div>&ndash;&gt;&ndash;&gt;-->
<!--&lt;!&ndash;        <div&ndash;&gt;-->
<!--&lt;!&ndash;          class="carousel-item h-100"&ndash;&gt;-->
<!--&lt;!&ndash;          :style="{&ndash;&gt;-->
<!--&lt;!&ndash;            backgroundImage:&ndash;&gt;-->
<!--&lt;!&ndash;              'url(' + require('@/assets/img/carousel-2.jpg') + ')',&ndash;&gt;-->
<!--&lt;!&ndash;            backgroundSize: 'cover',&ndash;&gt;-->
<!--&lt;!&ndash;          }"&ndash;&gt;-->
<!--&lt;!&ndash;        >&ndash;&gt;-->
<!--&lt;!&ndash;          <div&ndash;&gt;-->
<!--&lt;!&ndash;            class="carousel-caption d-none d-md-block bottom-0 text-start start-0 ms-5"&ndash;&gt;-->
<!--&lt;!&ndash;          >&ndash;&gt;-->
<!--&lt;!&ndash;            <div&ndash;&gt;-->
<!--&lt;!&ndash;              class="icon icon-shape icon-sm bg-white text-center border-radius-md mb-3"&ndash;&gt;-->
<!--&lt;!&ndash;            >&ndash;&gt;-->
<!--&lt;!&ndash;              <i class="ni ni-bulb-61 text-dark opacity-10"></i>&ndash;&gt;-->
<!--&lt;!&ndash;            </div>&ndash;&gt;-->
<!--&lt;!&ndash;            <h5 class="text-white mb-1">Faster way to create web pages</h5>&ndash;&gt;-->
<!--&lt;!&ndash;            <p>&ndash;&gt;-->
<!--&lt;!&ndash;              That’s my skill. I’m not really specifically talented at anything&ndash;&gt;-->
<!--&lt;!&ndash;              except for the ability to learn.&ndash;&gt;-->
<!--&lt;!&ndash;            </p>&ndash;&gt;-->
<!--&lt;!&ndash;          </div>&ndash;&gt;-->
<!--&lt;!&ndash;        </div>&ndash;&gt;-->
<!--&lt;!&ndash;        <div&ndash;&gt;-->
<!--&lt;!&ndash;          class="carousel-item h-100"&ndash;&gt;-->
<!--&lt;!&ndash;          :style="{&ndash;&gt;-->
<!--&lt;!&ndash;            backgroundImage:&ndash;&gt;-->
<!--&lt;!&ndash;              'url(' + require('@/assets/img/carousel-3.jpg') + ')',&ndash;&gt;-->
<!--&lt;!&ndash;            backgroundSize: 'cover',&ndash;&gt;-->
<!--&lt;!&ndash;          }"&ndash;&gt;-->
<!--&lt;!&ndash;        >&ndash;&gt;-->
<!--&lt;!&ndash;          <div&ndash;&gt;-->
<!--&lt;!&ndash;            class="carousel-caption d-none d-md-block bottom-0 text-start start-0 ms-5"&ndash;&gt;-->
<!--&lt;!&ndash;          >&ndash;&gt;-->
<!--&lt;!&ndash;            <div&ndash;&gt;-->
<!--&lt;!&ndash;              class="icon icon-shape icon-sm bg-white text-center border-radius-md mb-3"&ndash;&gt;-->
<!--&lt;!&ndash;            >&ndash;&gt;-->
<!--&lt;!&ndash;              <i class="ni ni-trophy text-dark opacity-10"></i>&ndash;&gt;-->
<!--&lt;!&ndash;            </div>&ndash;&gt;-->
<!--&lt;!&ndash;            <h5 class="text-white mb-1">Share with us your design tips!</h5>&ndash;&gt;-->
<!--&lt;!&ndash;            <p>&ndash;&gt;-->
<!--&lt;!&ndash;              Don’t be afraid to be wrong because you can’t learn anything from&ndash;&gt;-->
<!--&lt;!&ndash;              a compliment.&ndash;&gt;-->
<!--&lt;!&ndash;            </p>&ndash;&gt;-->
<!--&lt;!&ndash;          </div>&ndash;&gt;-->
<!--&lt;!&ndash;        </div>&ndash;&gt;-->
<!--&lt;!&ndash;      </div>&ndash;&gt;-->
<!--      <button-->
<!--        class="carousel-control-prev w-5 me-3"-->
<!--        type="button"-->
<!--        data-bs-target="#carouselExampleCaptions"-->
<!--        data-bs-slide="prev"-->
<!--      >-->
<!--        <span class="carousel-control-prev-icon" aria-hidden="true"></span>-->
<!--        <span class="visually-hidden">Previous</span>-->
<!--      </button>-->
<!--      <button-->
<!--        class="carousel-control-next w-5 me-3"-->
<!--        type="button"-->
<!--        data-bs-target="#carouselExampleCaptions"-->
<!--        data-bs-slide="next"-->
<!--      >-->
<!--        <span class="carousel-control-next-icon" aria-hidden="true"></span>-->
<!--        <span class="visually-hidden">Next</span>-->
<!--      </button>-->
<!--    </div>-->
  </div>
</template>
