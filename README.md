/* Base styles for positioning and typography */
.position-absolute { position: absolute; }
.position-relative { position: relative; }
.font-outfit { font-family: 'Outfit', sans-serif; }
.font-lato { font-family: 'Lato', sans-serif; }
.text-white { color: #FFFFFF; }
.text-black { color: #000000; }
.text-center { text-align: center; }
.bg-plum { background: #7C2946; }

/* Layout */
.frame-40 {
  position: relative;
  width: 2134px;
  height: 6000px;
}

.lifestyle-office {
  position: absolute;
  width: 1440px;
  height: 1080px;
  left: 135px;
  top: 0;
  background: linear-gradient(0deg, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)), url(.png);
}

.rectangle {
  position: absolute;
  width: 368px;
  height: 154px;
  background: #7C2946;
  border-radius: 20px;
}
.rectangle-73 { left: 879px; top: 1430px; }
.rectangle-72 { left: 456px; top: 1430px; }
.rectangle-19 { width: 915px; height: 100px; left: 291px; top: 809px; }
.rectangle-27 { width: 1711px; height: 141px; left: 0; top: 3290px; }
.rectangle-23 { width: 1527px; height: 476px; left: 48px; top: 5524px; border-radius: 30px 0px 0px 0px; }
.rectangle-26 { width: 1839px; height: 128px; left: 295px; top: 3996px; border-radius: 90px 0px 0px 90px; }

/* Text Styles */
.title {
  font-weight: 700;
  font-size: 100px;
  line-height: 126px;
  color: #FFFFFF;
}
.title-plum { width: 603px; height: 111px; left: 405px; top: 678px; }

.subtitle {
  font-weight: 700;
  font-size: 48px;
  line-height: 60px;
  text-align: center;
  color: #000000;
}

.mission {
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 24px;
  color: #1D1D1D;
  width: 1012px;
  height: 168px;
  left: 349.23px;
  top: 1114px;
  transform: rotate(0.05deg);
}

/* Flexbox Layouts */
.flex-column {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0px;
  gap: 20px;
}

.flex-row {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
  gap: 267px;
}

/* Additional styles for specific elements can be added as needed, focusing on reusing classes for common patterns */

