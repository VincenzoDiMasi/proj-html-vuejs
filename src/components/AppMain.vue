<script>
import BuildYourDreamsCards from './BuildYourDreamsCards.vue';
import DataValue from './DataValue.vue';
import CardCourses from './CardCourses.vue';
import CardEvents from './CardEvents.vue';
export default {
  name: 'AppMain',
  components: {BuildYourDreamsCards, DataValue, CardCourses, CardEvents,},
  data() {
    return {
      
      cardsBuildYourDream: [
                {
                    img: 'src/assets/img/home-5-image-box-01.png',
                    title: 'Idea Discussion',
                    text: 'Get teamed up with specialists who work and teach coding for years at famous universities.',
                    button: 'Start now',
                    id: 1
                },
                {
                    img: 'src/assets/img/home-5-image-box-02.png',
                    title: 'Web Development',
                    text: 'Learn to start building a webpage from scratch. You decide your own pace, course and speed.',
                    button: 'Start now',
                    id: 2
                },
                {
                    img: 'src/assets/img/home-5-image-box-03.png',
                    title: 'System Administration',
                    text: 'Learners are encouraged to study the mechanism and structure of system administration.',
                    button: 'Start now',
                    id: 3
                },
                {
                    img: 'src/assets/img/home-5-image-box-04.png',
                    title: 'Graphic Design',
                    text: 'Have a passion for graphic and arts? Show your talent with confidence and self-assertiveness.',
                    button: 'Start now',
                    id: 4
                },
                
               
            ],
      
      numbers: [
        {
          title: '1.926',
          text: 'FINISHED LESSONS',
          id: 1,
        },
        {
          title: '3.092+',
          text: 'ENROLLED LEARNERS',
          id: 2,
        },
        {
          title: '200',
          text: 'ONLINE INSTRUCTURES',
          id: 3,
        },
        {
          title: '100%',
          text: 'SATISFACTION RATE',
          id: 4,
        },
      ],
      cardsCareer: [
                {
                    mainImg: 'src/assets/img/course-02-480x298.jpg',
                    badge: '$40.00',
                    proPic: 'src/assets/img/73ee246daf47502812ccefc84bf02898.jpeg',
                    name: 'Blanche Fields',
                    text: 'Learning to Write as a Professional Author',
                    students: '50 students',
                    lessons: ' 20 lessons',
                    id: 1
                },
                {
                    mainImg: 'src/assets/img/stock-full-hd-03-480x298.jpg',
                    badge: 'Free',
                    proPic: 'src/assets/img/d0d504142acfde820eef2f11feea6253.jpeg',
                    name: 'Maggie Strickland',
                    text: 'Customer-centric Info-Tech Strategies',
                    students: '769 students',
                    lessons: ' 24 lessons',
                    id: 2
                },
                {
                    mainImg: 'src/assets/img/stock-full-hd-04-480x298.jpg',
                    badge: '$19.00',
                    proPic: 'src/assets/img/d0d504142acfde820eef2f11feea6253.jpeg',
                    name: 'Maggie Strickland',
                    text: 'Open Programming Courses for everyone: Python',
                    students: '62 students',
                    lessons: ' 17 lessons',
                    id: 3
                },
                {
                    mainImg: 'src/assets/img/stock-full-hd-06-480x298.jpg',
                    badge: '$26.00',
                    proPic: 'src/assets/img/73ee246daf47502812ccefc84bf02898.jpeg',
                    name: 'Blanche Fields',
                    text: 'Academic Listenings and Note-taking',
                    students: '57 students',
                    lessons: ' 14 lessons',
                    id: 4
                },
                {
                    mainImg: 'src/assets/img/course-featured-image-01-480x298.jpg',
                    badge: '$39.00',
                    proPic: 'src/assets/img/73ee246daf47502812ccefc84bf02898.jpeg',
                    name: 'Blanche Fields',
                    text: 'Master jQuery in a Short Period of Time',
                    students: '51 students',
                    lessons: ' 6 lessons',
                    id: 5
                },
                {
                    mainImg: 'src/assets/img/stock-full-hd-05-480x298.jpg',
                    badge: '$40',
                    proPic: 'src/assets/img/73ee246daf47502812ccefc84bf02898.jpeg',
                    name: 'Blanche Fields',
                    text: 'Introduction to JavaScript for Beginners',
                    students: '50 students',
                    lessons: ' 20 lessons',
                    id: 6
                },
                
               
            ],
       cardsEvent: [
                {
                    gps: 'Texas, U.S.',
                    name: 'Storytelling Workshop',
                    day: '22',
                    month: 'NOV',
                    button: 'Get ticket',
                    id: 1
                },
                {
                    gps: 'New York, U.S.',
                    name: 'Painting Art Contest 2020',
                    day: '10',
                    month: 'OCT',
                    button: 'Get ticket',
                    id: 2
                },
                {
                    gps: 'Hamburg, Germany',
                    name: 'International Art Fair 2020',
                    day: '22',
                    month: 'JUL',
                    button: 'Get ticket',
                    id: 3
                },
                {
                    gps: 'Illinois, U.S.',
                    name: 'Street Performance: Call for Artist',
                    day: '15',
                    month: 'DEC',
                    button: 'Get ticket',
                    id: 4
                },
                {
                    gps: 'Illinois, U.S.',
                    name: 'Consumer Food Safety Education Conference',
                    day: '22',
                    month: 'JUL',
                    button: 'Get ticket',
                    id: 5
                },
                {
                    gps: 'Dubai',
                    name: 'How meditation improve your mental health?',
                    day: '12',
                    month: 'AUG',
                    button: 'Get ticket',
                    id: 6
                },
                
                
               
            ],  
       cardsReview: [
                  {
                    img: 'src/assets/img/testimonial-avata-02.jpg',
                    text: 'I am free to learn at my own pace, follow my own schedule and choose the subject I like. Great study portal for people like me.',
                    name: 'MINA HOLLACE',
                    subtitle: '/Freelancer',
                    id: 1
                },
                {
                    img: 'src/assets/img/testimonial-avata-01.jpg',
                    text: 'MaxCoach is my best choice. Their tutors are smart and professional when dealing with students.',
                    name: 'MADLEY PONDOR',
                    subtitle: '/IT Specialist',
                    id: 2
                },
                {
                    img: 'src/assets/img/testimonial-avata-03.jpg',
                    text: 'I am happy with their arrangement of lessons and subjects. They reflect a scientific investigation.',
                    name: 'LUVIC DUBBLE',
                    subtitle: '/Private Tutor',
                    id: 3
                },
       ],            
            
    };      
              
  },
  methods: {
    // Your component methods 
  },
  computed: {
    // Computed properties 
  },
  created() {
    // Lifecycle hook 
  }
};
</script>

<template>
  <main>

    <!-- BUILD YOUR TEAM -->
    <section id="build-your-team" class="container text-center mt-5">
      <h6 class="grey-title">START LEARNING CODING LANGUAGES</h6>
      <div class="d-flex justify-content-center">
        <h1>Build Your Dream</h1>
        <h1 class="highlighted">TODAY</h1>
      </div>
      
      <div class="container d-flex mt-5 mb-5">
        <div class="row">
          <!-- CARD DINAMICALLY GENERATED -->
          <BuildYourDreamsCards v-for="card in cardsBuildYourDream" :card="card" :key="card.id"></BuildYourDreamsCards>
        </div>
      </div>
      
    </section>

    <!-- CAREER SECTION -->
    <section id="career" class="container my-5">
      <div class="row">
        <div class="col ms-5 underlay">
          <!-- <img class="underlay" src="../assets/img/underlay-shape-lilla.svg" alt=""> -->
          <img src="../assets/img/about-us-03-image-01.png" alt="">
          
        </div>
        <div class="col">
          <h6 class="grey-title">DREAM WITH MAXCOACH</h6>
          <div>
            <h1>Construct A <span class="highlighted">Stunning</span>  <br> Career Perspective</h1>        
          </div>
          <div class="menu-item-green d-flex justify-content-between mt-4">
            <p>Multiple Platforms Supported for Teaching & Studying </p> <a href="#"><i class="fa-solid fa-circle-minus text-white"></i></a>
          </div>
          <div class="text-item">
            <p>MaxCoach supports the act of teaching and learning on multiple platforms like online or offline via material downloads. We know things aren't supposed to be devoured in a short time, you can always access our knowledge base from any device.  </p>
          </div>
          <div class="menu-item d-flex justify-content-between mt-4">
            <p>Multiple Course Partecipatiom at the Same Time </p> <a href="#"><i class="fa-solid fa-circle-plus"></i></a>
          </div>
          <div class="menu-item d-flex justify-content-between mt-4">
            <p>Track Study Progress & Deliver Prompt Feedback </p> <a href="#"><i class="fa-solid fa-circle-plus"></i></a>
          </div>
        </div>
      </div>


    </section>

    <!-- DATA VALUE SECTION -->
    <section id="numbers">
      <div class="container pt-5 ">
        <div class="row">
          <!-- DATA VALUE NUMBERS FROM ARRAY DATA  -->
          <DataValue v-for="number in numbers" :number="number" :key="number.id"></DataValue>
        </div>
      </div>
    </section>

    <!-- COURSES SECTION -->
    <section id="courses" class=" text-center mt-5 ">
      <div class="container">
        <h6 class="grey-title">CHOOSE WHERE YOU'D LIKE TO BEGAN</h6>
      <h1 class="mb-5">Latest Featured <span class="highlighted">Courses</span></h1>  
      <div class="row row-cols-3">
        <!-- COURSES CARDS FROM ARRAY DATA -->
        <CardCourses v-for="card in cardsCareer" :card="card" :key="card.id" ></CardCourses>
      </div>
      <a href="#" class="btn btn-green fw-bold mb-5">View all courses<i class="fa-solid fa-arrow-right-long txt-wht"></i></a>
      </div>
     

    </section>

    <!-- PACE SECTION -->
    <section id="pace-learn" class="mt-5 container">
      <div class="row">
        <div class="col mrgn">
          <h6 class="grey-title">WHY HESITATE TO REGISTER?</h6>
          <div>
            <h1>Learn At Your <br> Own<span class="highlighted">Pace</span></h1>        
          </div>
          <ul class="check-list">
            <!-- FEATURES LIST -->
            <li><i class="fa-solid fa-check"></i>Select & customize courses to your preferences</li>
            <li><i class="fa-solid fa-check"></i>Change the tutor and make arrangements</li>
            <li><i class="fa-solid fa-check"></i>Participate in events to join others</li>
            <li><i class="fa-solid fa-check"></i>Get the desires certificate delivered at house</li>
            
          </ul>

          <a href="#" class="btn btn-green fw-bold my-3">Get started for free<i class="fa-solid fa-arrow-right-long txt-wht"></i></a>

          
        </div>
        <div class="col ms-5 underlay">
          
          <img src="../assets/img/home-5-image-01.png" alt="">
          
        </div>
        
      </div>
    </section>

    <!-- WHERE SECTION -->
    <section id="where-learn" class="mt-5 container">
      <div class="row">
        <div class="col ms-5 underlay">
          
          <img src="../assets/img/home-5-image-02.png" alt="">
          
        </div>
        <div class="col-5 w-25">
          <h6 class="grey-title">WHAT ARE YOU LOOKING FOR?</h6>
          <div>
            <h1>Learn On Your <span class="highlighted">mobile</span> Anytime!</h1> 
            <p class="mt-4">Save lessons for later and revise or write notes at any time and on multiple devices on your way. Never interfere with activities of enjoyment or others precious moments.</p>       
            <a href="#" class="btn btn-green fw-bold my-3">Download our App</a>
          </div>
        </div>

      </div>


    </section>

    <!-- EVENTS SECTION -->
    <section id="events" class=" text-center mt-5 container">
      <h6 class="grey-title">GET IN CONTACT NOW</h6>
      <h1 class="mb-5">Upcoming <span class="highlighted">Events</span></h1>        
      <div  class="row row-cols-2">

        <!-- EVENTS GENERATED FROM ARRAY DATA -->
       <CardEvents v-for="card in cardsEvent" :card="card" :key="card.id"></CardEvents>
      </div>

      <h5 class="my-5">Excited about our events? <span ><a class="highlighted" href="#">View all events <i class="fa-solid fa-arrow-right-long txt-brnd"></i></a> </span></h5>
    </section>

    <!-- REVIEWS SECTION -->
    <section id="reviews" class=" text-center mt-5 ">
      <div class="container">
        <h6 class="grey-title pt-5">PEOPLE ARE PRAISING MAX COACH</h6>
        <h1 class="mb-5">What make they <span class="highlighted">Love Us?</span></h1>  
        <div class="row row-cols-3">
          <!-- REVIEWS FROM ARRAY DATA -->
          <div v-for="card in cardsReview" class="col">
            <div class="review-card mb-5">
              <img class="rounded-image" :src="card.img" alt="">
              <p>{{ card.text }}</p>
              <h6 class="text-center">{{ card.name }}</h6>
              <p class="subtitle grey-title">{{ card.subtitle }}</p>
            </div>
          </div>
        </div>   
      </div>
      
    </section>

    <!-- C2A SECTION -->
    <section id="c2a">
      <div class="container">
        <div class="row" style="padding-top: 110px;">
          <div class="col-2 left-col">
            <figure>
              <img src="../assets/img/maxcoach-shape-01.png" alt="">
            </figure>
          </div>
          <div class="col-8 central-col text-center">
            <h6 class="">Start today for getting<span class="highlighted">Online Certification</span></h6>
            <h3 class="">You can be your own guiding star with our help!</h3>
            <a href="#" class="btn btn-green mt-4">Get started now</a>
          </div>
          <div class="col-2 right-col">
            <figure>
              <img src="../assets/img/maxcoach-shape-02.png" alt="">
            </figure>
          </div>
        </div>
      </div>
    </section>
  </main>

</template>

<style lang="scss" scoped>
@import "../assets/styles/variables.scss";
// section {
//   min-height: 400px;
// }
#career {

  .underlay {
    background-image: url('../assets/img/underlay-shape-lilla.svg');
    background-repeat: no-repeat;
    background-position: 0% 40%;
    background-size: 350px;

    img {
    margin-left: 120px;
    height: 450px;
  }


  }
    .menu-item-green {
    background-color: $brandColor;
    border-radius: 10px 10px 0 0 ;
    border: 1px solid $brandColor;
    height: 50px;
    padding: 10px;

    
    
    
    p {
      color: white;
      font-weight: bold;

    }
  }

  .text-item {
    box-shadow: 2px 4px #dcdbdb;
    background-color: $bgSecondaryColor;
    border-radius: 0 0 10px 10px;
    padding: 10px;

    p{
      color: $textSecondaryColor;
      font-size: 12px;
    }
  }

.menu-item {
    height: 50px;
    padding: 10px;
    box-shadow: 2px 4px #dcdbdb;

    border: 1px solid white;
    background-color: $bgSecondaryColor;
    

    p,.fa-circle-plus {
      color: $textSecondaryColor;
      font-weight: bold;

    }
    }

}

#numbers {
  height: 170px;
  background-color: $bgBeige;
  padding: 0 200px;

 
}

#courses {
  padding: 0 200px;
  background-color: $bgSecondaryColor;
  .row {
    position: relative;

  }
 

    .txt-wht {
      color: $bgMainColor;
      margin-left: 5px;
    }

}

#pace-learn {

  .mrgn {
    margin-left: 120px;

    .check-list {
      margin-top: 30px;
      margin-left: -25px;
      li {
        margin-bottom: 10px;
         .fa-check {
      color: $brandColor;
      margin-right: 10px;
    }
      }

     
    }
   

    .txt-wht {
      color: $bgMainColor;
      margin-left: 5px;
    }

    
  }
  .underlay {
    background-image: url('../assets/img/underlay-shape-grey.svg');
    background-repeat: no-repeat;
    background-position: 0% 40%;
    background-size: 350px;

    img {
    margin-left: 120px;
    height: 450px;
  }
}
}

#where-learn {
  .underlay {
    background-image: url('../assets/img/underlay-shape-grey.svg');
    background-repeat: no-repeat;
    background-position: 0% 40%;
    background-size: 350px;
    margin-right: -585px;

    img {
    margin-left: 120px;
    height: 450px;
  }
}

.grey-title {
  margin-top: 80px;
}
  

    .txt-wht {
      color: $bgMainColor;
      margin-left: 5px;
    }

}

#events {
  margin-bottom: 30px;
 
  .txt-brnd {
    color: $brandColor;
  }
}

#reviews {
  background-color: $bgSecondaryColor;
  .review-card {
    // border: 1px solid grey;
    background-color: $bgMainColor;
    margin-top: 150px;
    border-radius: 20px;
    height: 400px;
    padding: 5px;
    

    .rounded-image {
      position: relative;
      bottom: 95px;
    }
  }
}

#c2a {
  height: 350px;
  background-color: $bgSecondaryColor;

  

  
}

</style>