<!DOCTYPE html>
<html lang="en">
<body style="font-family: Arial, sans-serif; line-height: 1.6; padding: 20px;">

<h1 style="text-align: center;">Foundry: A Beginner's Guide</h1>

<h2>Getting Started</h2>
<p>Foundry is a Web3 development framework designed to simplify building decentralized applications (dApps) on compatible blockchains like Ethereum. It's written in Rust, offering speed, portability, and modularity.</p>

<h2>Benefits of Foundry</h2>
<ul>
  <li>Speed: Known for its fast performance due to Rust's high-performance nature.</li>
  <li>Portability: Can be used on any platform and deployed to various blockchain networks.</li>
  <li>Modularity: Offers flexibility by allowing developers to choose required tools.</li>
  <li>Security: Equipped with security features like contract verification to safeguard applications.</li>
  <li>Community: Supported by an active community providing assistance and support.</li>
  <li>Tests in Solidity: Unique feature allowing writing tests in Solidity itself, reducing context-switching costs.</li>
</ul>

<h2>Frameworks in Ethereum Development</h2>
<p>Alongside Foundry, developers have other options for Ethereum development:</p>
<ul>
  <li>Truffle</li>
  <li>Hardhat</li>
  <li>Brownie</li>
  <li>Embark</li>
  <li>Waffle</li>
</ul>

<h2>Components of Foundry</h2>
<p>Foundry consists of various components catering to different aspects of development:</p>
<ul>
  <li>Forge: Ethereum testing framework for writing and running tests in Solidity.</li>
  <li>Cast: Tool for interacting with EVM smart contracts, sending transactions, and getting blockchain data.</li>
  <li>Anvil: Local Ethereum node for testing applications locally with multiple nodes and network configurations.</li>
  <li>Chisel: Solidity REPL for compiling, running, and debugging Solidity code.</li>
</ul>

<h2>Getting Started with Foundry</h2>
<p>Once Foundry is installed, follow these steps to initialize a project directory:</p>

<ol>
  <li>Type the following command in the terminal:</li>
</ol>

<pre><code>forge init foundry-demo</code></pre>

<ol start="2">
  <li>Check if the project is initialized correctly:</li>
</ol>

<pre><code>cd foundry-demo &amp;&amp; forge build</code></pre>

<p>Expected output in your terminal is shown in the 'Expected output' image for reference.</p>

<h2>Understanding Project Structure</h2>
<p>Here's an explanation of the main files and folders you'll interact with:</p>

<ul>
  <li><b>lib:</b> Contains project dependencies, similar to 'node_modules' in some JavaScript frameworks.</li>
  <li><b>script:</b> Executes smart contracts for state transitions or complex deployments using Solidity.</li>
  <li><b>src:</b> Holds all your smart contracts.</li>
  <li><b>test:</b> Contains test cases for your smart contracts.</li>
  <li><b>out:</b> Stores ABIs (Application Binary Interfaces) of compiled smart contracts.</li>
</ul>

</body>
</html>
