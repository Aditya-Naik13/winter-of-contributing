<h1 color=cyan>What is a Flexbox?</h1>
<p>The Flexible Box Layout Module usually referred to as Flexbox is a layout in CSS3, makes it easier to design flexible responsive layout structure without using float or positioning.</p>
<pUsing Flexbox is a good choice to use in CSS so you can design the page responsively.</p>
<p>It was designed as a one-dimensional layout model, and as a method that could offer space distribution between items in an interface and powerful alignment capabilities.</p>
<br>
<h2>How it works?</h2>
<p>Flexbox deals with layout in one dimension at a time — either as a row or as a column.</P>
<p>When working with flexbox you need to think in terms of two axes — the main axis and the cross axis. The main axis is defined by the flex-direction property, and the cross axis runs perpendicular to it. Everything we do with flexbox refers back to these axes, so it is worth understanding how they work from the outset.</p>
<p>To use flexbox give property of display: flex; to element for using flexbox.</p>
<img src="https://res.cloudinary.com/practicaldev/image/fetch/s---3gDSFf1--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/fsln7je4ax7ft3er28hh.png">
<p>You can get the basic idea of the layout by seeing the above image. There are two elements placed inside the flex container(the one to which the the display:flex property is assigned). These elements can be positoned in differnt ways desired by the user by the help of flex properties.</p>
<p>As of now they are aligned inline to each other as shown in the image.</p> 
<p>The main axis is defined by flex-direction, which has four possible values:</p>
<ul>
<li>row</li>
<li>row-reverse</li>
<li>column</li>
<li>column-reverse</li>
</ul>
<p>Should you choose row or row-reverse, your main axis will run along the row in the inline direction.</p>
<img src=https://res.cloudinary.com/practicaldev/image/fetch/s----O5J3PQ--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/4jkkaafn2ef4osrtmhyg.png>
