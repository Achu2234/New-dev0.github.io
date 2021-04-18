<div align="center">
    <h2>TgTwitterBot</h2><br>
    <img src="../tgtwitterbot/20210418_004643.png" width="500"><br>
    <p><i>Telegram - Twitter - Bot</i></p>
</div>
<p><a href="https://github.com/New-dev0/TgTwitterBot">
TgTwitterBot</a> can Help you to Control and Explore Twitter from Telegram.<br> It is Using <a href="https://github.com/Tweepy/Tweepy">Tweepy</a> to Interact with Twitter API.
</p>
<h2>Deployment Guide</h2>
<h3>Getting ENV's</h3>
<ol>
    <li>Create a <a href="https://developer.twitter.com/en">Twitter Developer Account</a>.<br><img src="https://1000logos.net/wp-content/uploads/2017/06/logo-Twitter-500x180.png" width="600"><br></li><br>
    <li>Go to Developer Portal/Dashboard.</li><br>
    <li>Create a Application and fill the details Asked !</li><br>
    <li>Change the App Setting to <code>Read + Write</code>.</li><br>
    <li>Go to <code>Keys and Token</code> Tab.</li><br>
    <li>You can see <code>Consumer Key</code>'s Heading<br><img src="https://telegra.ph/file/53cd6e806af38801df381.jpg" width="600"><br> Generate the Api Key & Secret<br> Generated Api Key will be <code>CONSUMER_KEY</code> and Api Secret will be <code>CONSUMER_SECRET</code><br>Which
        are Required in ENV.
    </li><br>
    <li>Check <i>Authentication Token</i><br><br><img src="https://telegra.ph/file/bc7b4923f87f48e0c1be2.jpg" width="600"><br>Generate Your Access Token and Secret.<br> Access Token will be <code>ACCESS_TOKEN</code><br> Access Secret will be <code>ACCESS_TOKEN_SECRET</code>,
        Required.
    </li>
    <br>
    <li>Add the User Id of users in <code>AUTHUSERS</code> Var. They will have Access to Use Your BOT.</li>
    <br>
    <li>Go to <a href="https://my.telegram.org">my.telegram.org</a><br>
        <ul type="square">
            <li>Login with Your Account.</li>
            <li>Go to <i color="black">API Development tools</i> Tab</li>
            <li>Create A Telegram APP.</li>
            <li>You will Get Your <code>API_ID</code> and <code>API_HASH</code></li>
        </ul><br>
    </li>
    <li>Go to <a href="https://t.me/botfather">@BotFather</a>
        <ul type="circle">
            <li>Create a Bot and you will get Bot Token.</li>
            <li>Fill it as <code>BOT_TOKEN</code></li>
</ol>
</li><br>
<li>and Done !</li>
</ol>

<h3>Local Deploy</h3>
<ol>
    <li>Clone the Github Repo.<br>
        <code>git clone https://github.com/New-dev0/TgTwitterBot.git<br>cd TgTwitterBot</code>
    </li><br>
    <li>Install Requirements<br><code>pip install -r requirements.txt</code></li><br>
    <li>Start The Bot<br><code>python -m twitterbot</code></li>
</ol>
