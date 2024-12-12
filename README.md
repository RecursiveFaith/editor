<h1>EDITOR - an evolving interface</h1>
<blockquote>[coming soon]</blockquote>

<br>
<hr>
<br>

<h1>Getting started</h1>

<h2>(option 1) Clone or download the source code locally</h2>
<blockquote>[coming soon]</blockquote>

<h2>(option 2) Copy + Paste the source code from a QR Code</h2>
<p>As a benchmark the goal is to keep the source code small enough to fit on a standard QR Code. "Standard QR Codes" range from version 1 to 40, or about 17 bytes to 2953 bytes of data. Those numbers are for raw byte data though, QR Codes can encode different types of data. For numeric characters the range is more like 41 - 7089 numeric characters or 25 - 4296 for alphanumerics</p>
<p>This is still very experimental and designed for easily loading onto devices that aren't connected. These codes are encoded with the raw text...paste it into a .html file, and then open it with a browser on that device</p>
<table>
  <thead>
    <tr>
      <th>
        <h4>Uncompressed</h4>
      </th>
      <th>
        <h4>Compressed</h4>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <div>QR Code version = 39</div>
        <div>character count = 2800</div>
        <div>data bits = 22420</div>
      </td>
      <td>
        <div>QR Code version = 33</div>
        <div>character count = 2061</div>
        <div>data bits = 16508</div>
      </td>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/ee7698f1-fa34-4692-b6f9-5a3d75e3d227" width=362>
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/134eb4a5-a8d7-45e5-827d-70228cab73e1" width=314>
      </td> 
    </tr>    
  </tbody>
</table>

<h3>Maximum Standard Limits</h3>
Version 40: 177x177 modules, can hold up to 7,089 numeric characters, 4,296 alphanumeric characters, 2,953 bytes of data, or 1,817 kanji characters

<h3>Generating QR Codes</h3>
For now I'm making them here: https://www.nayuki.io/page/qr-code-generator-library
