<h1 align="center">Polymarket Copy Trading Bot – CLOB API + RTDS (Node.js)</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/dev-protocol/polymarket-sports-crypto-copy-bot/main/public/s.gif" width="750" alt="Polymarket Copy Trading Bot Demo"/>
</p>

<p align="center">
<strong>Automated Polymarket Trading Bot</strong><br>
Real-time <strong>Copy Trading</strong> powered by <strong>Polymarket CLOB API</strong> and <strong>RTDS WebSocket Stream</strong> on Polygon.
</p>

<p align="center">
  <b>Polymarket Trading Bot</b> •
  <b>Copy Trading Automation</b> •
  <b>Prediction Market Bot</b> •
  <b>Polygon Web3 Bot</b> •
  <b>Node.js Trading Infrastructure</b>
</p>

<hr>

<h2>Overview</h2>

<p>
This project is a high-performance <strong>Polymarket copy trading bot</strong> built with <strong>Node.js + Express</strong>.
It listens to real-time wallet activity via <strong>RTDS (Real-Time Data Stream)</strong> and automatically replicates trades using the <strong>Polymarket CLOB API</strong>.
</p>

<p>
Designed for developers building:
</p>

<ul>
  <li>Polymarket automation tools</li>
  <li>Crypto prediction market bots</li>
  <li>Web3 trading infrastructure</li>
  <li>Whale copy trading systems</li>
  <li>Algorithmic trading strategies on Polygon</li>
</ul>

<hr>

<h2>Core Features</h2>

<ul>
  <li>Real-time wallet monitoring via Polymarket RTDS</li>
  <li>Instant trade replication (copy trading engine)</li>
  <li>CLOB API order execution</li>
  <li>Polygon (EVM) network integration</li>
  <li>Express backend architecture</li>
  <li>HTML frontend dashboard</li>
  <li>Private key signing (EOA)</li>
  <li>Automatic 401 / API key error recovery handling</li>
</ul>

<hr>

<h2>Technology Stack</h2>

<ul>
  <li><strong>Node.js</strong></li>
  <li><strong>Express.js</strong></li>
  <li><strong>Polymarket CLOB API</strong></li>
  <li><strong>Polymarket RTDS WebSocket</strong></li>
  <li><strong>Polygon (Ethereum-compatible network)</strong></li>
</ul>

<hr>

<h2>How the Polymarket Copy Trading Bot Works</h2>

<ol>
  <li>Connects to Polymarket RTDS WebSocket</li>
  <li>Monitors a target wallet’s trading activity</li>
  <li>Detects trade execution events</li>
  <li>Recreates orders through the CLOB API</li>
  <li>Signs transactions using your private key</li>
</ol>

<p>
This enables fully automated <strong>real-time Polymarket copy trading</strong>.
</p>

<hr>

<h2>Installation & Setup</h2>

<h3>1. Clone the Repository</h3>

<pre><code>git clone https://github.com/dev-protocol/polymarket-sports-crypto-copy-bot.git
cd polymarket-sports-crypto-copy-bot
</code></pre>

<h3>2. Install Dependencies</h3>

<pre><code>npm install
</code></pre>

<h3>3. Configure Environment Variables</h3>

<pre><code>cp .env.example .env
</code></pre>

<table>
<tr>
<th>Environment Variable</th>
<th>Required</th>
<th>Description</th>
</tr>
<tr>
<td><code>PRIVATE_KEY</code></td>
<td>Yes</td>
<td>EOA private key (0x...) linked to a Polymarket account</td>
</tr>
<tr>
<td><code>POLYGON_RPC_URL</code></td>
<td>No</td>
<td>Polygon RPC endpoint (default: https://polygon-rpc.com)</td>
</tr>
</table>

<hr>

<h2>Running the Bot</h2>

<pre><code>npm run build
npm start
</code></pre>

<p>For development mode:</p>

<pre><code>npx nodemon
</code></pre>

<hr>

<h2>Troubleshooting – 401 Unauthorized / Invalid API Key</h2>

If you encounter:

<ul>
<li><code>401 Unauthorized</code></li>
<li><code>Invalid API key</code></li>
</ul>

Possible causes:

<ul>
  <li>Your wallet is not linked to Polymarket</li>
  <li>The derived CLOB API key was revoked</li>
  <li>Region or API access restrictions</li>
</ul>

After a 401:
<ul>
  <li>The bot clears the CLOB client</li>
  <li>Stops heartbeats</li>
  <li>Requires restart after fixing credentials</li>
</ul>

<hr>

<h2>Security Best Practices</h2>

<ul>
  <li>Never commit your <code>.env</code> file</li>
  <li>Never share your private key</li>
  <li>Use a dedicated wallet for automation</li>
  <li>Limit funds in the trading wallet</li>
</ul>

<hr>

<h2>Use Cases</h2>

<ul>
  <li>Polymarket copy trading bot</li>
  <li>Whale trade replication</li>
  <li>Sports & crypto prediction market automation</li>
  <li>Algorithmic trading experiments</li>
  <li>Web3 trading bot infrastructure</li>
</ul>

<hr>

<h2>Search Keywords (Indexed by GitHub & Google)</h2>

<p>
Polymarket trading bot, Polymarket copy trading bot, Polymarket CLOB API example, Polymarket RTDS stream integration, Polygon trading bot, crypto prediction market automation, Web3 trading bot Node.js, Polymarket sports trading bot, crypto copy trading system, blockchain prediction market bot.
</p>

<hr>

<h2>Disclaimer</h2>

<p>
This project is provided for educational and research purposes only.
Trading prediction markets involves financial risk.
Use at your own risk.
</p>
