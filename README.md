<h1 class="code-line" data-line-start=1 data-line-end=2 ><a id="BankCTF_1"></a>BankCTF</h1>
<p class="has-line-data" data-line-start="2" data-line-end="3"><em>by jacvbtaylor</em></p>
<p class="has-line-data" data-line-start="5" data-line-end="6">I created this CTF with the intent to help individuals who are wanting to learn how to hack but do not have any experiences doing so.</p>
<p class="has-line-data" data-line-start="7" data-line-end="8">You will need access to an attacker virtual machine in order to investigate agaisnt this CTF machine.</p>
<p class="has-line-data" data-line-start="9" data-line-end="10"><em>If you aren’t sure how to do that, follow the steps here:</em></p>
<pre><code class="has-line-data" data-line-start="11" data-line-end="13" class="language-sh">https://www.youtube.com/watch?v=wX75Z-<span class="hljs-number">4</span>MEoM&amp;ab_channel=NetworkChuck
</code></pre>
<blockquote>
<p class="has-line-data" data-line-start="14" data-line-end="18">Note: <code>[!!!!] IMPORTANT [!!!!]</code><br>
If you have both machines running but you cannot locate the IP for the CTF machine in STEP 2,<br>
try changing the network settings on your VM’s.<br>
You should not have any issues if both are running on bridged mode</p>
</blockquote>
<p class="has-line-data" data-line-start="21" data-line-end="23">Bank CTF has a detailed guide/walkthrough for players that get stuck or are brand new to CTF’s<br>
&amp; was created with a beginner’s approach in mind to capture 6 flags.</p>
<p class="has-line-data" data-line-start="24" data-line-end="25">The objectives are to:</p>
<ul>
<li class="has-line-data" data-line-start="25" data-line-end="26">Download the CTF machine</li>
<li class="has-line-data" data-line-start="26" data-line-end="27">Locate it on your network via Nmap</li>
<li class="has-line-data" data-line-start="27" data-line-end="28">Find open ports</li>
<li class="has-line-data" data-line-start="28" data-line-end="29">Run dirb to find secret website pages</li>
<li class="has-line-data" data-line-start="29" data-line-end="30">Use hydra to bruteforce a website login</li>
<li class="has-line-data" data-line-start="30" data-line-end="31">Bruteforce SSH login</li>
<li class="has-line-data" data-line-start="31" data-line-end="32">Escalate privilegs</li>
<li class="has-line-data" data-line-start="32" data-line-end="33">Exploit a program to dump /etc/passwd</li>
<li class="has-line-data" data-line-start="33" data-line-end="34">Create a wordlist using crunch</li>
<li class="has-line-data" data-line-start="34" data-line-end="36">Become root</li>
</ul>
<p class="has-line-data" data-line-start="36" data-line-end="41">INTRO<br>
Roger at work mentioned a new bank opening up in one of the small towns in your area.<br>
He said someone had reached out to him about designing their website but he declined<br>
because the pay was going to be too little and said whoever ends up building the site<br>
probably won’t know what they are doing.</p>
<p class="has-line-data" data-line-start="42" data-line-end="43">You decide you want to check out the site and look for some vulnerabilities…</p>
<h1 class="code-line" data-line-start=46 data-line-end=47 ><a id="Goodluck_46"></a>Goodluck!</h1>
