<h1>Setup a SSH Deamon on g Colab instance</h1> 
 <p>Setup a SSH Server on the instance and then expose the ssh port via a ngrok TCP Tunnel, Then use that tunnel to SSH into the box</p>

<ul>
<li>GO through each cell and run it </li>
<li>Mount Your GDrive to access files from google drive</li>
<li>Replace the password in the notebook to make a new password for root</li>
<li>Once it Prompts for authtoken, Enter the ngrok auth token from your ngrok dashboard</li>
<li>Then Check for the tunnel URL and port in output</li>
<li>Onto your machine, ssh using command <b>ssh roo@tunnelurl -p tunnelport</b></li>
</ul>