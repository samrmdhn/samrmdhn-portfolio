<template>
    <div style="margin-top:20px">
        <div class="judul paragraph2">TABLE OF CONTENTS</div>
        <b-container style="margin-top: 20px">
            <div class="content-center pickaz" style="margin: 0 auto; font-weight: bolder; color: #d3ff52;">Pick a card</div>
            <b-row>
                <a href="#education" class="kartu1">
                    <div class="kartu1-depan">
                            <div class="position-relative">
                                <div class="position-absolute" style="color: black; font-size: 10rem; margin-top: 160px; margin-left: 10px">1</div>
                                <div style="color: black; padding-top: 20px; padding-left: 100px">EDUCATION</div>
                            </div>
                    </div>
                    <div class="kartu1-belakang">
                        <div><br><p>Click to go to Education</p></div>
                    </div>
                </a>
                
                <a href="#work" class="kartu2">
                    <div class="kartu2-depan">
                            <div class="position-relative">
                                <div class="position-absolute" style="color: black; font-size: 10rem; margin-top: 160px; margin-left: 10px">2</div>
                                <div style="color: black; padding-top: 20px; padding-left: 100px">WORK EXPERIENCE</div>
                            </div>
                    </div>
                    <div class="kartu2-belakang">
                         <div><br><p>Click to go to Work Experience</p></div>
                    </div>
                </a>

                <a href="#projects" class="kartu3">
                    <div class="kartu3-depan">
                            <div class="position-relative">
                                <div class="position-absolute" style="color: black; font-size: 10rem; margin-top: 160px; margin-left: 10px">3</div>
                                <div style="color: black; padding-top: 20px; padding-left: 100px">PROJECTS AND DESIGN</div>
                            </div>
                    </div>
                    <div class="kartu3-belakang">
                        <div><br><p>Click to go to Projects & Design</p></div>
                    </div>
                </a>

                <a href="#contact" class="kartu4">
                    <div class="kartu4-depan">
                            <div class="position-relative">
                                <div class="position-absolute" style="color: white; font-size: 10rem; margin-top: 160px; margin-left: 10px">4</div>
                                <div style="color: white; padding-top: 20px; padding-left: 100px">CONTACT</div>
                            </div>
                    </div>
                    <div class="kartu4-belakang">
                         <div><br><p>Click to go to Contact</p></div>
                    </div>
                </a>

            </b-row>
        </b-container>
    </div>
</template>
<script>
export default {
    name: "tableContents"
}
</script>
<style scoped>
    .judul{
        font-size: 3rem;
    }

    .kartu1 {
        height: 360px;
        width: 250px;
        margin: 10px;
        transform-style: preserve-3d;
        transition: all 1s ease;
    }

    .kartu1:hover{
        transform: rotateY(180deg);
    }

    .kartu1-depan{
  position: absolute;
  height: 360px;
  width: 250px;
  border-radius: 5px;
  backface-visibility: hidden;
  overflow: hidden;
  background: #d3ff52;
  color: #000;
    }

    .kartu1-belakang{
  position: absolute;
  height: 360px;
  width: 250px;
  border-radius: 5px;
  backface-visibility: hidden;
  overflow: hidden;
  background: #d3ff52;
  color: #000;
  text-align: center;
  transform: rotateY(180deg);
    }

.kartu2 {
        height: 360px;
        width: 250px;
        margin: 10px;
        border-color: grey;
        transform-style: preserve-3d;
        transition: all 1s ease;
    }

    .kartu2:hover{
        transform: rotateY(180deg);
    }

    .kartu2-depan{
  position: absolute;
  height: 360px;
  width: 250px;
  border-radius: 5px;
  backface-visibility: hidden;
  overflow: hidden;
  background: white;
  color: #000;
    }

    .kartu2-belakang{
  position: absolute;
  height: 360px;
  width: 250px;
  border-radius: 5px;
  backface-visibility: hidden;
  overflow: hidden;
  background: #fafafa;
  color: #333;
  text-align: center;
  transform: rotateY(180deg);
    }

.kartu3{
        height: 360px;
        width: 250px;
        margin: 10px;
        border-color: grey;
        transform-style: preserve-3d;
        transition: all 1s ease;
    }

    .kartu3:hover{
        transform: rotateY(180deg);
    }

    .kartu3-depan{
  position: absolute;
  height: 360px;
  width: 250px;
  border-radius: 5px;
  backface-visibility: hidden;
  overflow: hidden;
  background: grey;
  color: #000;
    }

    .kartu3-belakang{
  position: absolute;
  height: 360px;
  width: 250px;
  border-radius: 5px;
  backface-visibility: hidden;
  overflow: hidden;
  background: grey;
  color: #000;
  text-align: center;
  transform: rotateY(180deg);
    }

.kartu4{
        
        height: 360px;
        width: 250px;
        margin: 10px;
        transform-style: preserve-3d;
        transition: all 1s ease;
    }

    .kartu4:hover{
        transform: rotateY(180deg);
    }

    .kartu4-depan{
        border-style: solid;
        border-width: 0.5px;
        border-radius: 5px;
        border-color: white;
  position: absolute;
  height: 360px;
  width: 250px;
  border-radius: 5px;
  backface-visibility: hidden;
  overflow: hidden;
  background: #000;
  color: #000;
    }

    .kartu4-belakang{
        border-style: solid;
        border-width: 0.5px;
        border-radius: 5px;
        border-color: white;
  position: absolute;
  height: 360px;
  width: 250px;
  border-radius: 5px;
  backface-visibility: hidden;
  overflow: hidden;
  background: #000;
  color: white;
  text-align: center;
  transform: rotateY(180deg);
    }

@media screen and (min-width: 350px) {
    .kartu1{
        margin: 10px auto 10px auto;
    }
    .kartu2{
        margin: 10px auto 10px auto;
    }
    .kartu3{
        margin: 10px auto 10px auto;
    }
    .kartu4{
        margin: 10px auto 10px auto;
    }

}

</style>