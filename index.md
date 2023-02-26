---
layout: page
title: Welcome
subtitle: Stefan Wallentowitz, professor at Munich University of Applied Sciences
---

On these pages you can learn more about my teaching, research and other
activities. In the following you find the highlights of my work, navigate the
menu for more.

{% capture teaching_note %}

I teach in the topics of *computer architecture, computer organization,
embedded system security* and *operating systems*. Beside the lectures I
am very enthusiastic about practical labs, and have created useful tools
available for wider use (see [projects](/projects)).

Students can browse my regular [courses](/courses), the actual courses are on my
university's moodle. If you are looking for a [thesis](/theses-jobs) please
check the listings or get in touch with me regarding your own ideas. I also have
[jobs](/theses-jobs) available for students and PhD candidates.

{% endcapture %}

{% capture riscv_note %}

<a href="https://riscv.org" target="_blank">RISC-V</a> is an open instruction
set architecture, that has gained a lot of traction over the last years. It
enables innovation in future silicon chips as an open computing standard.

I have long been involved in RISC-V and I am very active in advocacy of the
RISC-V in Germany and Europe, for example on the board of directors of RISC-V.
RISC-V is very present in my own education and my students value the highly
relevant content with the vivid spirit of this growing open ecosystem.

{% endcapture %}

{% capture wasm_note %}

WebAssembly is a standard for managed virtual machines. Such managed virtual
machines are based on bytecode that is interpreted on different platforms.
Thereby it has interesting security properties.

With my background in smartcards, where JavaCard is dominant, I started working
on WebAssembly for embedded systems. While WebAssembly originated in the
browser, it is by-design much more low level than Java for example. It is an
excellent candidate for scalable IoT systems.

{% endcapture %}

<article>
  <div class="row maincontent">
    <div class="col-12">
        <img src="/assets/img/teaching.png" class="float-sm-right" style="width: 18em; padding: 2em; border-radius: 3em;">
        {{ teaching_note | markdownify }}
    </div>
  </div>
</article>

<article>
  <div class="row maincontent">
    <div class="col-12">
        <img src="/assets/img/riscv.png" class="float-sm-left" style="width: 18em; padding: 2em;">
        {{ riscv_note | markdownify }}
    </div>
  </div>
</article>

<article>
  <div class="row maincontent">
    <div class="col-12">
        <img src="/assets/img/wasm4iot.png" class="float-sm-right" style="float: right; width: 18em; padding: 2em;">
        {{ wasm_note | markdownify }}
    </div>
  </div>
</article>
