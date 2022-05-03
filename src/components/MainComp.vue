<template>

  <div>

    <div class="bg-g-gray">

        <div class="text_center p_50">
            <span class="text_uppercase">start learning coding languages</span>
            <h2 class="text_capital fs_8">build your dream <span class="text_uppercase text_jungle">today</span></h2>
        </div>

        <div id="sec-1" class="container-default d_flex justify_between">
            <div class="flexColAJCenter">
                <img class="" src="../assets/img/work-element/home-5-image-box-01.png" alt="ideas">
                <h4 class="text_capital text_center fs_4">idea discussion</h4>
                <p class="text_center fs_2">
                    Get teamed up with the specialist who
                    work and teach coding for years at
                    famous universities.
                </p>
                <h5 class="start text_mulled-wine text_center fs_2" >Start now <i class="start text_mulled-wine fa-solid fa-arrow-right-long"></i></h5>
            </div>
            <div class="flexColAJCenter">
                <img src="../assets/img/work-element/home-5-image-box-02.png" alt="web">
                <h4 class="text_capital text_center fs_4">web development</h4>
                <p class="text_center fs_2">
                    Learn to start building a webpage from scratch.
                    You decide your own pace, course and speed.
                </p>
                <h5 class="start text_mulled-wine text_center fs_2" >Start now <i class="start text_mulled-wine fa-solid fa-arrow-right-long"></i></h5>
            </div>
            <div class="flexColAJCenter">
                <img src="../assets/img/work-element/home-5-image-box-03.png" alt="systems">
                <h4 class="text_capital text_center fs_4">system administration</h4>
                <p class="text_center fs_2">
                    Learners are encouraged to study the mechanism and structure of system
                    administration.
                </p>
                <h5 class="start text_mulled-wine text_center fs_2" >Start now <i class="start text_mulled-wine fa-solid fa-arrow-right-long"></i></h5>
            </div>
            <div class="flexColAJCenter">
                <img src="../assets/img/work-element/home-5-image-box-04.png" alt="graphics">
                <h4 class="text_capital text_center fs_4">graphic design</h4>
                <p class="text_center fs_2">
                    Have a passion for graphics and arts?
                    Show your talents with confidence and
                    self-assertiveness.
                </p>
                <h5 class="start text_mulled-wine text_center fs_2" >Start now <i class="start text_mulled-wine fa-solid fa-arrow-right-long"></i></h5>
            </div>
        </div>

        <div class="container-default flexBetween_2 p-y-50 ">
            <div>
                <img src="../assets/img/work-element/about-us-03-image-01.png" alt="">
            </div>
            <div class="d_flex flex_col w_50">
                <div class="text_start">
                    <span class="text_uppercase">dream with <span class="fw_b">maxcoach</span></span>
                    <h2 class="text_capital fs_8">construct a <span class="text_capital text_jungle">stunning</span> career perspective</h2>
                </div>
                <div class="justify_start">
                    
                    <!-- Paragrafo Dropdown -->
                    <div class="bg-custom-white p_10 flexRowWrap align_center" style="width: 450px" v-if="isActive">
                        <h4 class="b_rounded_1">
                            <span class="text_capital">multiple platforms supported</span> for <span class="text_capital">teaching & studying</span>
                        </h4>
                        <i class="p_s_20 fa-solid fa-circle-plus fs_3 pewter" @click="getShowAct(active)"></i>
                    </div>    
                    <div v-if="active">
                        <h4 class="bg-jungle-green text_white p_20 b_rounded_1">
                            <span class="text_capital">multiple platforms supported</span> for <span class="text_capital">teaching & studying</span>
                            <i class="p_s_70 fa-solid fa-circle-minus" @click="getShowIsAct(isActive)"></i>
                        </h4>
                        <p class="p_20 b_rounded_1">
                            MaxCoach supports the act of teaching and learning on multiple
                            platforms like online or offline via meterial downloads.
                            We know things aren't supposed to be devoured in a short time, you
                            can always access our knowledge base from any device.
                        </p>
                    </div> 
                    

                    <div class="bg-custom-white p_10 flexRowWrap align_center m_y_40" style="width: 450px" v-if="isActive">
                        <h4 class="b_rounded_1">
                            <span class="text_capital">multiple platforms supported</span> for <span class="text_capital">teaching & studying</span>
                        </h4>
                        <i class="p_s_20 fa-solid fa-circle-plus fs_3 pewter" @click="getShowAct(active)"></i>
                    </div>    
                    <div v-if="active">
                        <h4 class="bg-jungle-green text_white p_20 b_rounded_1">
                            <span class="text_capital">multiple platforms supported</span> for <span class="text_capital">teaching & studying</span>
                            <i class="p_s_70 fa-solid fa-circle-minus" @click="getShowIsAct(isActive)"></i>
                        </h4>
                        <p class="p_20 b_rounded_1">
                            MaxCoach supports the act of teaching and learning on multiple
                            platforms like online or offline via meterial downloads.
                            We know things aren't supposed to be devoured in a short time, you
                            can always access our knowledge base from any device.
                        </p>
                    </div> 
     

                    <div class="bg-custom-white p_10 flexRowWrap align_center" style="width: 450px" v-if="isActive">
                        <h4 class="b_rounded_1">
                            <span class="text_capital">multiple platforms supported</span> for <span class="text_capital">teaching & studying</span>
                        </h4>
                        <i class="p_s_20 fa-solid fa-circle-plus fs_3 pewter" @click="getShowAct(active)"></i>
                    </div>    
                    <div v-if="active">
                        <h4 class="bg-jungle-green text_white p_20 b_rounded_1">
                            <span class="text_capital">multiple platforms supported</span> for <span class="text_capital">teaching & studying</span>
                            <i class="p_s_70 fa-solid fa-circle-minus" @click="getShowIsAct(isActive)"></i>
                        </h4>
                        <p class="p_20 b_rounded_1">
                            MaxCoach supports the act of teaching and learning on multiple
                            platforms like online or offline via meterial downloads.
                            We know things aren't supposed to be devoured in a short time, you
                            can always access our knowledge base from any device.
                        </p>
                    </div> 

                </div>
            </div>
        </div>
    </div>

    <div id="divider" class="bg-gallery flexRowWrap">
        <div class="container-default flexBetween">
            <div class="text_center">
                <span class="fs_7 text_jungle fw_b">1.926</span>
                <div class="text_uppercase fw_b">finished sessions</div>
            </div>
            <div class="text_center">
                <span class="fs_7 text_jungle fw_b">3.092+</span>
                <div class="text_uppercase fw_b">enrolled learners</div>
            </div>
            <div class="text_center">
                <span class="fs_7 text_jungle fw_b">200</span>
                <div class="text_uppercase fw_b">online instructors</div>
            </div>
            <div class="text_center">
                <span class="fs_7 text_jungle fw_b">100%</span>
                <div class="text_uppercase fw_b">satisfaction rate</div>
            </div>

        </div>
    </div>

    <div id="sec-2">

        <div class="container-default">

            <div class="text_center p_50">
                <span class="text_uppercase ">choose where you'd like to begin</span>
                <h2 class="text_capital fs_8">latest featured <span class="text_capital text_jungle">courses</span></h2>
            </div>

            <ul class="listTypeNone flexRowWrap">
                <li class="card">

                    <div id="image_1" class="imageCard b_top_left_right p_relative">
                        <h5 class="p_absolute b_rounded_1 bg-jungle-green m_t_0 fw_b text_white p_10" style="top: 0; right: 0; "><span class="fs_3">$40</span>.00</h5>
                    </div>

                    <div class="container-default-2">
                        <div class="d_flex align_center p_t_10">
                            <img class="b_rounded_5" src="../assets/img/work-element/73ee246daf47502812ccefc84bf02898.jpeg" alt="Blanche Fields">
                            <span class="text_capital p_s_10">blanche fields</span>
                        </div>
                        <h4 class="w_85">Learning to Write as a Professional Author</h4>
                        <div class="d_flex align_center">
                            <span class="d_flex align_center p_e_10"><img class="p_e_5" style="width: 15px; height: 15px;" src="../assets/Icons/icons8-documento-24.png" alt=""> 20 Lessons</span>
                            <span class="d_flex align_center p_s_5"><i class="fa-solid fa-user p_e_5" style="width: 15px; height: 15px;"></i>50 Students</span>
                        </div>
                    </div>
                </li>
                <li class="card">
                    <div id="image_2" class="imageCard b_top_left_right p_relative">
                        <h5 class="p_absolute b_rounded_1 bg-jungle-green m_t_0 fw_b text_white p-y-10 p-x-15 text_capital" style="top: 0; right: 0; "><span class="fs_3">free</span></h5>
                    </div>
                    <div class="container-default-2">
                        <div class="d_flex align_center p_t_10">
                            <img class="b_rounded_5" src="../assets/img/work-element/d0d504142acfde820eef2f11feea6253.jpeg" alt="Maggie Strickland">
                            <span class="text_capital p_s_10">maggie strickland</span>
                        </div>
                        <h4 class="w_85">Learning to Write as a Professional Author</h4>
                        <div class="d_flex align_center">
                            <span class="d_flex align_center p_e_10"><img class="p_e_5" style="width: 15px; height: 15px;" src="../assets/Icons/icons8-documento-24.png" alt=""> 24 Lessons</span>
                            <span class="d_flex align_center p_s_5"><i class="fa-solid fa-user p_e_5" style="width: 15px; height: 15px;"></i>769 Students</span>
                        </div>
                    </div>
                </li>
                <li class="card">
                    <div id="image_3" class="imageCard b_top_left_right p_relative">
                        <h5 class="p_absolute b_rounded_1 bg-jungle-green m_t_0 fw_b text_white p_10" style="top: 0; right: 0;"><span class="fs_3">$19</span>.00</h5>
                    </div>
                    <div class="container-default-2">
                        <div class="d_flex align_center p_t_10">
                            <img class="b_rounded_5" src="../assets/img/work-element/d0d504142acfde820eef2f11feea6253.jpeg" alt="Maggie Strickland">
                            <span class="text_capital p_s_10">maggie strickland</span>
                        </div>
                        <h4 class="w_85">Open Programming Courses for Everyone: Python</h4>
                        <div class="d_flex align_center">
                            <span class="d_flex align_center p_e_10"><img class="p_e_5" style="width: 15px; height: 15px;" src="../assets/Icons/icons8-documento-24.png" alt=""> 17 Lessons</span>
                            <span class="d_flex align_center p_s_5"><i class="fa-solid fa-user p_e_5" style="width: 15px; height: 15px;"></i>62 Students</span>
                        </div>
                    </div>
                </li>
                <li class="card">
                    <div id="image_4" class="imageCard b_top_left_right p_relative">
                        <h5 class="p_absolute b_rounded_1 bg-jungle-green m_t_0 fw_b text_white p_10" style="top: 0; right: 0; "><span class="fs_3">$26</span>.00</h5>
                    </div>
                    <div class="container-default-2">
                        <div class="d_flex align_center p_t_10">
                            <img class="b_rounded_5" src="../assets/img/work-element/73ee246daf47502812ccefc84bf02898.jpeg" alt="Maggie Strickland">
                            <span class="text_capital p_s_10">blanche fields</span>
                        </div>
                        <h4 class="w_85">Academic Listening and Note-taking</h4>
                        <div class="d_flex align_center">
                            <span class="d_flex align_center p_e_10"><img class="p_e_5" style="width: 15px; height: 15px;" src="../assets/Icons/icons8-documento-24.png" alt=""> 14 Lessons</span>
                            <span class="d_flex align_center p_s_5"><i class="fa-solid fa-user p_e_5" style="width: 15px; height: 15px;"></i>67 Students</span>
                        </div>
                    </div>
                </li>
                <li class="card">
                    <div id="image_5" class="imageCard b_top_left_right p_relative">
                        <h5 class="p_absolute b_rounded_1 bg-jungle-green m_t_0 fw_b text_white p_10" style="top: 0; right: 0; "><span class="fs_3">$39</span>.00</h5>
                    </div>
                    <div class="container-default-2">
                        <div class="d_flex align_center p_t_10">
                            <img class="b_rounded_5" src="../assets/img/work-element/73ee246daf47502812ccefc84bf02898.jpeg" alt="Maggie Strickland">
                            <span class="text_capital p_s_10">blanche fields</span>
                        </div>
                        <h4 class="w_85">Master jQuery in a Short Period of Time</h4>
                        <div class="d_flex align_center">
                            <span class="d_flex align_center p_e_10"><img class="p_e_5" style="width: 15px; height: 15px;" src="../assets/Icons/icons8-documento-24.png" alt=""> 6 Lessons</span>
                            <span class="d_flex align_center p_s_5"><i class="fa-solid fa-user p_e_5" style="width: 15px; height: 15px;"></i>51 Students</span>
                        </div>
                    </div>
                </li>
                <li class="card">
                    <div id="image_6" class="imageCard b_top_left_right p_relative">
                        <h5 class="p_absolute b_rounded_1 bg-jungle-green m_t_0 fw_b text_white p_10" style="top: 0; right: 0; "><span class="fs_3">$59</span>.00</h5>
                    </div>
                    <div class="container-default-2">
                        <div class="d_flex align_center p_t_10">
                            <img class="b_rounded_5" src="../assets/img/work-element/73ee246daf47502812ccefc84bf02898.jpeg" alt="Maggie Strickland">
                            <span class="text_capital p_s_10">blanche fields</span>
                        </div>
                        <h4 class="w_85">Introduction to Javascript for Beginners</h4>
                        <div class="d_flex align_center">
                            <span class="d_flex align_center p_e_10"><img class="p_e_5" style="width: 15px; height: 15px;" src="../assets/Icons/icons8-documento-24.png" alt=""> 14 Lessons</span>
                            <span class="d_flex align_center p_s_5"><i class="fa-solid fa-user p_e_5" style="width: 15px; height: 15px;"></i>76 Students</span>
                        </div>
                    </div>
                </li>
            </ul>
            <div class="m_70 flexRowWrap p_b_70">
                <button class="btt p-y-15 p-x-50 b_none b_rounded_1 bg-jungle-green text_white fw_b fs_2"
                        style="cursor: pointer;">View all courses
                        <i class="vertical_middle p_s_5 fa-solid fa-arrow-right-long"></i>
                </button>
            </div>

        </div>

    </div>

    <div id="sec-3" class="container-default flexBetween_2 p_y_120">

        <div class="d_flex flex_col w_35">
            <div class="text_start">
                <span class="text_uppercase">why hesitate to register?</span>
                <h2 class="text_capital fs_8 fw_b">learn at your own <span class="text_capital text_jungle">pace</span></h2>
            </div>
            <ul id="ul-check-sec-3" class="flexColWrap">
                <li class="p-y-10">
                    <i class="text_jungle fw_b fa-solid fa-check p_e_10"></i>
                    <span>Select & customize courses to your preferences</span>
                </li>
                <li class="p-y-10">
                    <i class="text_jungle fw_b fa-solid fa-check p_e_10"></i>
                    <span>Change the tutor and make arrangements</span>
                </li>
                <li class="p-y-10">
                    <i class="text_jungle fw_b fa-solid fa-check p_e_10"></i>
                    <span>Participate in events to join others</span>
                </li>
                <li class="p-y-10">
                    <i class="text_jungle fw_b fa-solid fa-check p_e_10"></i>
                    <span>Get the desired certificate delivered at house</span>
                </li>
                <li class="p-y-30">
                    <button class="btt p-y-20 p-x-50 b_none b_rounded_1 bg-jungle-green text_white fw_b fs_2"
                            style="cursor: pointer;">Get started for free</button>
                </li>
            </ul>
        </div>
        <div  class="flexBetween_2 align_end p_relative">
            <div id="img-sec-3" class="" >

            </div>
            <div class="align_self_center p_t_60">
                <img src="../assets/img/work-element/maxcoach-shape-05.png" alt="">
            </div>
            <div class="p_absolute">
                 <img class="" style="margin-left: 100px; margin-bottom: 50px" src="../assets/img/work-element/home-5-image-01.png" alt="">
            </div>
        </div>

    </div>

    <div id="sec-3-part-2" class="container-default-1 flexBetween_2 p_y_120">

        <div  class="flexBetween_2 align_end p_relative">
            <div class="align_self_center">
                <img style="padding-bottom: 70px" src="../assets/img/work-element/maxcoach-shape-01.png" alt="">
            </div>
            <div style="margin-left: -50px" id="img-sec-3" class="" >

            </div>
            <div class="align_self_center p_t_60">
                <img src="../assets/img/work-element/maxcoach-shape-07.png" alt="">
            </div>
            <div class="p_absolute">
                 <img class="" style="margin-left: 250px; margin-bottom: 30px" src="../assets/img/work-element/home-5-image-02.png" alt="">
            </div>
             <div class="b_circle_orange m_y_20 align_self_start" style="height: 35px; width: 35px;margin-left: -40px"></div>
        </div>

        <div class="d_flex flex_col w_35">
            <div class="text_start">
                <span class="text_uppercase">what are you looking for?</span>
                <h2 class="text_capital fs_8 fw_b">learn on your <span class="text_jungle">mobile</span> anytime!</h2>
            </div>
            <ul id="ul-check-sec-3" class="flexColWrap">
                <li class="p-y-10">
                    <p>
                        Save lessons for later and revise or write notes at any
                        time and on multiple devices on your way.
                        Never interfere with activities of enjoyment or
                        other precious moments.
                    </p>
                </li>
                <li class="p-y-30">
                    <button class="btt p-y-20 p-x-50 text_capital b_none b_rounded_1 bg-jungle-green text_white fw_b fs_2"
                            style="cursor: pointer;">downoload our app</button>
                </li>
            </ul>
        </div>

    </div>
    <div id="sec-3-part-3">
        <div class="container-default-1 p-y-10">
            <div class="text_center">
                <span class="text_uppercase">get in contact now</span>
                <h2 class="text_capital fs_8 fw_b">upcoming <span class="text_jungle text_capital">events</span></h2>
            </div>
            <ul id="ul-events-sec-3" class="flexRowWrap">
                <li class="hovCard flexBetween m_10 p-y-20">
                    <div class="container-default-2 flexBetween">
                        <div>
                            <span><i class="fa-solid fa-location-dot m_e_5"></i> Texas, US</span>
                            <h4 class="text_capital fw_b">storytelling workshop</h4>
                        </div>
                        <div class="flexColWrap align_center">
                            <span class="text_uppercase fw_b fs_7 text_jungle">22</span>
                            <span class="text_uppercase m_y_5 fs_0 fw_b">nov</span>
                            <button class="btt p-y-10 p-x-40 b_none b_rounded_1 bg-jungle-green text_white fw_b fs_2"
                                    style="cursor: pointer;">Get ticket</button>
                        </div>
                    </div>
                </li>
                <li class="hovCard flexBetween m_10 p-y-20">
                    <div class="container-default-2 flexBetween">
                        <div>
                            <span><i class="fa-solid fa-location-dot m_e_5"></i> New York, US</span>
                            <h4 class="text_capital fw_b">Painting Art Contest 2020</h4>
                        </div>
                        <div class="flexColWrap align_center">
                            <span class="text_uppercase fw_b fs_7 text_jungle">10</span>
                            <span class="text_uppercase m_y_5 fs_0 fw_b">oct</span>
                            <button class="btt p-y-10 p-x-40 b_none b_rounded_1 bg-jungle-green text_white fw_b fs_2"
                                    style="cursor: pointer;">Get ticket</button>
                        </div>
                    </div>
                </li>
                <li class="hovCard flexBetween m_10 p-y-20">
                    <div class="container-default-2 flexBetween">
                        <div>
                            <span><i class="fa-solid fa-location-dot m_e_5"></i> Hamburg, Germany</span>
                            <h4 class="text_capital fw_b">international art fair 2020</h4>
                        </div>
                        <div class="flexColWrap align_center">
                            <span class="text_uppercase fw_b fs_7 text_jungle">23</span>
                            <span class="text_uppercase m_y_5 fs_0 fw_b">nov</span>
                            <button class="btt p-y-10 p-x-40 b_none b_rounded_1 bg-jungle-green text_white fw_b fs_2"
                                    style="cursor: pointer;">Get ticket</button>
                        </div>
                    </div>
                </li>
                <li class="hovCard flexBetween m_10 p-y-20">
                    <div class="container-default-2 flexBetween">
                        <div>
                            <span><i class="fa-solid fa-location-dot m_e_5"></i> Illinois, US</span>
                            <h4 class="text_capital fw_b">street performance: call for artist</h4>
                        </div>
                        <div class="flexColWrap align_center">
                            <span class="text_uppercase fw_b fs_7 text_jungle">15</span>
                            <span class="text_uppercase m_y_5 fs_0 fw_b">dec</span>
                            <button class="btt p-y-10 p-x-40 b_none b_rounded_1 bg-jungle-green text_white fw_b fs_2"
                                    style="cursor: pointer;">Get ticket</button>
                        </div>
                    </div>
                </li>
                <li class="hovCard flexBetween m_10 p-y-20">
                    <div class="container-default-2 flexBetween">
                        <div>
                            <span><i class="fa-solid fa-location-dot m_e_5"></i> Illinois, US</span>
                            <h4 class="text_capital fw_b w_85">consumer food safety education conference</h4>
                        </div>
                        <div class="flexColWrap align_center">
                            <span class="text_uppercase fw_b fs_7 text_jungle">22</span>
                            <span class="text_uppercase m_y_5 fs_0 fw_b">jul</span>
                            <button class="btt p-y-10 p-x-40 b_none b_rounded_1 bg-jungle-green text_white fw_b fs_2"
                                    style="cursor: pointer;">Get ticket</button>
                        </div>
                    </div>
                </li>
                <li class="hovCard flexBetween m_10 p-y-20">
                    <div class="container-default-2 flexBetween">
                        <div>
                            <span><i class="fa-solid fa-location-dot m_e_5"></i> Dubai</span>
                            <h4 class="text_capital fw_b w_85">how meditation improve your mental health?</h4>
                        </div>
                        <div class="flexColWrap align_center">
                            <span class="text_uppercase fw_b fs_7 text_jungle">12</span>
                            <span class="text_uppercase m_y_5 fs_0 fw_b">aug</span>
                            <button class="btt p-y-10 p-x-40 b_none b_rounded_1 bg-jungle-green text_white fw_b fs_2"
                                    style="cursor: pointer;">Get ticket</button>
                        </div>
                    </div>
                </li>

                <div class="p_t_50 p_b_200">
                    <h3>
                        Exited about our event? <span class="text_jungle" style="cursor: pointer"> View all events </span>
                        <i class="text_jungle fa-solid fa-arrow-right-long" style="cursor: pointer"></i>
                    </h3>
                </div>
            </ul>
        </div>
    </div>

    <div id="sec-3-part-4">
        <div class="container-default-1 p-y-30">
            <div class="text_center m_y_15">
                <span class="text_uppercase">people are praising maxcoach</span>
                <h2 class="fs_8 fw_b">What make they <span class="text_jungle">love us?</span></h2>
            </div>

            <SlickComp/>

            <div class="text_center p_t_100">
                <h3 class="fw_b">Start today for getting <span class="text_jungle text_capital">online certification</span></h3>
                <div class="flexRowWrap">
                    <div class="p_e_50">
                        <div class="b_circle_orange m_y_20" style="height: 35px; width: 35px;"></div>
                        <img style="padding-bottom: 70px" src="../assets/img/work-element/maxcoach-shape-01.png" alt="">
                    </div>
                    <div>
                        <h2 class="fs_8 fw_b">You can be your own guiding star with our help! </h2>
                        <button class="btt p-y-20 p-x-50 text_capital b_none b_rounded_1 bg-jungle-green text_white fw_b fs_2"
                                style="cursor: pointer;">Get started now</button>
                    </div>
                    <div class="p_t_150">
                        <img src="../assets/img/work-element/maxcoach-shape-02.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

</template>

<script>
import SlickComp from './SlickComp.vue'

export default {
  name: 'MainComp',
  components: {
      SlickComp,
  },

  data() {
      return {
          active: false,
          isActive: true,
          counter: 0,
      }
  },

  methods: {
      getShowAct(index) {
          console.log(index);
        if(!this.active == true & !this.isActive == false){
            this.active = true;
            this.isActive = false;
        }  else {
            this.active = false
            this.isActive = true;
        } return
    },

    getShowIsAct(i) {
        console.log(i)
        if(this.isActive == false & this.active == true){
            this.isActive = true;
            this.active = false;
        }  else {
            this.isActive = false;
            this.active = true;
        } return
    },

  }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/general.scss';

    #sec-1 h5 {
        cursor: pointer;
    }

    #drop {
        @include paddingButton;
    }

    #divider {
        height: 150px;
    }

    #sec-2 {
        background-image: url('../assets/img/general/vector-3.png');
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
    }

    .card {
        width: calc((100% / 3) - 2%);
        margin: 10px;
    }

    .card:hover {
        background-color: white;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    }

    .imageCard {
        width: 320px;
        height: 200px;
        background-size: cover;
    }

    .btt:hover {
        background-color: $mulled-wine;
    }

    #image_1 {
        background-image: url('../assets/img/work-element/course-02-480x298.jpg');
    }

    #image_2 {
        background-image: url('../assets/img/work-element/stock-full-hd-03-480x298.jpg');
    }

    #image_3 {
        background-image: url('../assets/img/work-element/stock-full-hd-04-480x298.jpg');
    }

    #image_4 {
        background-image: url('../assets/img/work-element/stock-full-hd-06-480x298.jpg');
    }

    #image_5 {
        background-image: url('../assets/img/work-element/course-featured-image-01-480x298.jpg');
    }

    #image_6 {
        background-image: url('../assets/img/work-element/stock-full-hd-05-480x298.jpg');
    }

    #img-sec-3 {
        background-image: url('../assets/img/general/underlay-shape-grey.svg');
        background-size: contain;
        background-repeat: no-repeat;
        background-position: bottom;
        width: 450px;
        height: 500px;
    }

    #ul-check-sec-3,
    #ul-events-sec-3 {
        @include reset-list;
    }

    #ul-events-sec-3 li {
        width: calc((100% / 2) - 30px);
        background-color: $g-gray;
    }

    #sec-3-part-3 {
        background-image: url('../assets/img/general/wave_.png');
        background-position: bottom;
        background-size: contain;
        background-repeat: no-repeat;
    }

    #sec-3-part-4 {
        background-color: $g-gray;

    }

    .start:hover {
        color: $jungle-green;
    }

    .hovCard:hover {
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        border-left: 4px solid $jungle-green;
        border-left-style: inset;

    }

</style>
