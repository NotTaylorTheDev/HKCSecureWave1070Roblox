# HKC SecureWave1070 on Roblox
#### by TaylorGaming2019/NotTaylor
<p>The first ever HKC system that exists on Roblox, based off the Ae Surge system but it's heavily modified. </p>

<h3>ℹ️ Background Information</h3>
<p>The system is intended to function as a regular HKC SW1070 system but limited due ROBLOX being a hard ass to script with and me lacking the full developer knowledge to script a full system from scratch.</p>
<p>However, the system is "heavily" modified to act like a HKC system (the keypad mostly) with it's programmed LEDs to light up on different events to it's beep that sounds the same as the SW1070 keypad.</p>
<p>There is however, a HUGE limitation as the system is not under the umbrella of support any more, meaning it's gone open source and open to attacks - so I wouldn't recommend this fully as a system for a popularly played game.</p>

<h3>🪲 Known Bugs</h3>
<ul>
  <li>The system is known to loop audio due to roblox not having a "IsPlaying" element to use. Line is <code>VoiceArmed.IsPlaying = true</code>
    <br>, but instead now uses <code>VoiceArmed.Playing = true</code> which makes the code loop the audio continously.</li>
  <li>The system's default smoke detector tends to bug out ALOT causing the system to go into fire constantly.</li>
  <li>Panic Button doesn't work, or I just don't know where to put it.</li>
  <li>LCD SurfaceGUI has the "?" in the wrong place for partial arm names. (working on it.)</li>
 </ul>
 
 <h3>🛠️ What's Planned</h3>
 <ul>
  <li>Webhook Sender - if I can code it to work. (don't get your hopes up.)</li>
  <li>A hotfix for the audio loop issue.</li>
  <li>A beta test version of the system.</li>
  <li>Some minor updates/tweaks.</li>
  <li>Visual Look Finish - need to finish the panel design e.g. the buttons.</li>
  <br>
  <hr>
  <centre>
  <footer>Last updated 04/06/2023 at 02:29 a.m. - yes adhd done this to me.</footer>
  </centre>
