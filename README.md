<svg width="600" height="200" viewBox="0 0 600 200" xmlns="http://www.w3.org/2000/svg">
<defs>
<filter id="shadow" x="-50%" y="-50%" width="200%" height="200%">
<feDropShadow dx="2" dy="2" stdDeviation="2" flood-color="#000" flood-opacity="0.3"/>
</filter>
</defs>

<style>
.brick {
fill: #a5b4fc; /* Lavender Blue /
rx: 5;
filter: url(#shadow);
}
.brick.pink {
fill: #f472b6; / Pink /
}
.brick.blue {
fill: #60a5fa; / Blue /
}
.paddle {
fill: #f3f4f6; / Light Gray /
rx: 8;
filter: url(#shadow);
}
.ball {
fill: #ffffff; / White /
}
.text {
font-family: 'Inter', sans-serif;
font-weight: 700;
font-size: 18px;
fill: #1f2937; / Dark Gray */
}
</style>

<!-- Bricks -->

<g transform="translate(60, 20)">
<rect class="brick blue" x="0" y="0" width="40" height="20" />
<rect class="brick blue" x="50" y="0" width="40" height="20" />
<rect class="brick blue" x="100" y="0" width="40" height="20" />
<rect class="brick blue" x="150" y="0" width="40" height="20" />
<rect class="brick blue" x="200" y="0" width="40" height="20" />
<rect class="brick blue" x="250" y="0" width="40" height="20" />
<rect class="brick blue" x="300" y="0" width="40" height="20" />
<rect class="brick blue" x="350" y="0" width="40" height="20" />
<rect class="brick blue" x="400" y="0" width="40" height="20" />

<rect class="brick pink" x="25" y="30" width="40" height="20" />
<rect class="brick pink" x="75" y="30" width="40" height="20" />
<rect class="brick pink" x="125" y="30" width="40" height="20" />
<rect class="brick pink" x="175" y="30" width="40" height="20" />
<rect class="brick pink" x="225" y="30" width="40" height="20" />
<rect class="brick pink" x="275" y="30" width="40" height="20" />
<rect class="brick pink" x="325" y="30" width="40" height="20" />
<rect class="brick pink" x="375" y="30" width="40" height="20" />

<rect class="brick" x="50" y="60" width="40" height="20" />
<rect class="brick" x="100" y="60" width="40" height="20" />
<rect class="brick" x="150" y="60" width="40" height="20" />
<rect class="brick" x="200" y="60" width="40" height="20" />
<rect class="brick" x="250" y="60" width="40" height="20" />
<rect class="brick" x="300" y="60" width="40" height="20" />
<rect class="brick" x="350" y="60" width="40" height="20" />
<rect class="brick" x="400" y="60" width="40" height="20" />

</g>

<!-- Paddle and Ball -->

<rect class="paddle" x="250" y="160" width="100" height="15" />
<circle class="ball" cx="300" cy="155" r="7" />

<!-- Text on Paddle -->

<text class="text" x="300" y="170" text-anchor="middle">My GitHub Profile</text>

</svg>
