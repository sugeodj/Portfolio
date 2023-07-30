---
navigation: false
---

# Today I Learned

<style>
    * {
	margin: 0;
	padding: 0;
}

ul {
	list-style: none;
	margin: 0 !important;
}

a {
	text-decoration: none !important;
	display: inline-block;
}

img {
	max-width: 100%;
}

button:focus {
	outline: none;
}

h1,
h2,
h3,
h4,
h5,
h6 {
	color: ;
	margin: 0;
}
p {
	font-size: 14px;
	line-height: 26px;
	margin: 0;
}
.container {
	width: 100%;
	max-width: 1140px;
	padding: 0 15px;
	box-sizing: border-box;
	margin: 0 auto;
}
.timelines h2 {
	text-align: center;
	color: #fff;
	font-weight: 600;
	margin-bottom: 40px;
	font-size: 32px;
}
.d-flex-2 {
	display: flex;
	align-items: center;
}
.timeline-area {
	padding: 80px 0;
}
.all-timelines {
	position: relative;
}
.timelines h2 {
	text-align: center;
	color: #fff;
	font-weight: 600;
	margin-bottom: 40px;
}
.all-timelines::before {
	content: "";
	position: absolute;
	left: 0;
	right: 0;
	margin: auto;
	height: 100%;
	width: 2px;
	background: #14b8a6;
	top: 20px;
}
.single-timeline {
	margin-bottom: 22px;
}
.timeline-blank {
	width: 50%;
}
.timeline-text {
	width: 50%;
	padding-left: 30px;
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
	position: relative;
}
.timeline-text h6 {
	font-weight: 900;
	display: inline-block;
	font-size: 1rem;
}
.timeline-text span {
	display: block;
	width: 100%;
}
.single-timeline:nth-child(even) .timeline-text span {
	text-align: right;
}
.t-square {
	content: "";
	position: absolute;
	width: 12px;
	height: 12px;
	left: -6px;
	background: #14b8a6;
}
.single-timeline:nth-child(even) {
	-webkit-box-orient: horizontal;
	-webkit-box-direction: reverse;
	-ms-flex-direction: row-reverse;
	flex-direction: row-reverse;
}
.single-timeline:nth-child(even) .t-square {
	right: -6px;
	left: unset;
}
.single-timeline:nth-child(even) .timeline-text {
	padding-left: 0;
	padding-right: 30px;
	text-align: right;
}

@media all and (max-width: 991px) {
}
@media all and (max-width: 768px) {
	.all-timelines::before {
		right: unset;
		top: 0;
	}
	.single-timeline:nth-child(2n) .timeline-text {
		padding-left: 30px;
		padding-right: 0;
		text-align: left;
	}
	.single-timeline:nth-child(2n) .t-square {
		left: -6px;
		right: unset;
	}
	.timeline-blank {
		display: none;
	}
	.timeline-text {
		width: 100%;
	}
	.single-timeline:nth-child(even) .timeline-text span {
		text-align: left !important;
	}
}
@media all and (max-width: 575px) {
}
@media all and (max-width: 360px) {
	.all-timelines::before {
		top: 32px;
	}
}

</style>

<body>
    <div class="timeline-area">
	<div class="container">
		<div class="all-timelines">
			<!--SINGLE TIMELINE-->
			<div class="single-timeline d-flex-2">
				<div class="timeline-blank"></div>
				<div class="timeline-text d-flex-2">
					<span>
						<strong>July 30th, 2023</strong><a href='til/pages/30-07-23'>Typescript ES5 Function</a> ~ You ask a small girl,"How old are you?" She always says, "x years old", where x is a random number between 0 and 9.
					</span>
					<div class="t-square"></div>
				</div>
			</div>
			<!--SINGLE TIMELINE-->
			<div class="single-timeline d-flex-2">
				<div class="timeline-blank"></div>
				<div class="timeline-text d-flex-2">
					<span>
						<strong>July 29th, 2023</strong><a href='til/pages/29-07-23'>Array.prototype.reduce()</a> ~  Given a non-empty array of integers, return the result of multiplying the values together in order.
					</span>
					<div class="t-square"></div>
				</div>
			</div>
		</div>
	</div>
</body>