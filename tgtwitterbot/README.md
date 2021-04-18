<div align="center">
    <h2>TgTwitterBot</h2><br>
    <img src="../tgtwitterbot/20210418_004643.png" width="500"><br>
    <p><i>Telegram - Twitter - Bot</i></p>
</div>
<p><a href="https://github.com/New-dev0/TgTwitterBot">
TgTwitterBot</a> can Help you to Control and Explore Twitter from Telegram.<br> It is Using <a href="https://github.com/Tweepy/Tweepy">Tweepy</a> to Interact with Twitter API.
</p>
<h2>Deployment Guide</h2><br>
<h3>Getting ENV's</h3><br>
<ol>
    <li>Create a <a href="https://developer.twitter.com/en">Twitter Developer Account</a>.</li>
    <li>Go to Developer Portal/Dashboard.</li>
    <li>Create a Application and fill the details Asked !</li>
    <li>Change the App Setting to <code>Read + Write</code>.</li>
    <li>Go to <code>Keys and Token</code> Tab.</li>
    <li>You can see <code>Consumer Key</code>'s Heading<br><img src="https://telegra.ph/file/53cd6e806af38801df381.jpg" width="600"><br> Generate the Api Key & Secret<br> Generated Api Key will be <code>CONSUMER_KEY</code> and Api Secret will be <code>CONSUMER_SECRET</code><br>Which
        are Required in ENV.
    </li><br>
    <li>Check <i>Authentication Token</i><br><br><img src="https://telegra.ph/file/bc7b4923f87f48e0c1be2.jpg" width="600"><br>Generate Your Access Token and Secret.<br> Access Token will be <code>ACCESS_TOKEN</code><br> Access Secret will be <code>ACCESS_TOKEN_SECRET</code>        Required to Tweet and other functions.</li>
    <li>Add the User Id of users in <code>AUTHUSERS</code> Var. AUTHUSERS will have Access to Use Your BOT.</li>
    <li>Go to <a href="https://my.telegram.org">my.telegram.org</a><br>
        <ul type="square">
            <li>Login with Your Account.</li><br>
            <li>Go to <i color="black">API Development tools</i> Tab</li>
            <li>Create A Telegram APP.</li>
            <li>You will Get Your <code>API_ID</code> and <code>API_HASH</code></li>
        </ul>
        <li>Go to <a href="https://t.me/botfather">@BotFather</a>
            <ol type="circle">
                <li>Create a Bot and you will get Bot Token.</li>
                <li>Fill it as <code>BOT_TOKEN</code></li>
            </ol>
        </li>
        <li>and Done !</li>
</ol>

<h3>Local Deploy</h3>
<ol>
    <li>Clone the Github Repo.<br>
        <code>git clone https://github.com/New-dev0/TgTwitterBot.git<br>cd TgTwitterBot</code>
    </li>
    <li>Install Requirements<br><code>pip install -r requirements.txt</code></li>
    <li>Start The Bot<br><code>python -m twitterbot</code></li>
</ol>
