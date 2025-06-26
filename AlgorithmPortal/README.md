📦 Data Compression & Decompression Portal
A web application that enables users to upload files and apply various data compression algorithms like Huffman Coding and Run-Length Encoding (RLE) to reduce file size. The application also supports decompression of files and presents compression efficiency metrics.

🚀 Project Description
This project provides a platform for compressing and decompressing files using efficient algorithms. It supports multiple file formats and evaluates the compression ratio, size difference, and processing time to help users choose the best method. It automatically selects the most efficient algorithm for compression and notifies the user if compression increases file size.

✨ Features
📤 File Upload: Upload text and binary files for compression/decompression.

⚙️ Multiple Compression Algorithms:

Huffman Coding

Run-Length Encoding (RLE)

🔄 Compression & Decompression: Switch between modes seamlessly.

📊 Compression Stats: Displays:

Original Size

Compressed Size

Compression Ratio

Processing Time

📥 Download Files: Users can download compressed/decompressed files.

📘 Algorithm Descriptions: Educates users with short descriptions of each algorithm.

❗ Error Handling: Alerts for unsupported formats and decompression issues.

📱 Responsive UI: Built with React and Tailwind CSS for optimal experience across devices.

🛠️ Tech Stack Used
Frontend
React.js — UI logic and state management

Tailwind CSS — Styling and responsiveness

JavaScript FileReader API — Reading and handling file metadata

Backend
Node.js + Express.js — API and compression logic

Custom Modules — Huffman and RLE written in JavaScript

Multer — File uploads

fs module — File I/O operations

Hosting
Frontend: Vercel (or Netlify)

Backend: Render (or Railway/Heroku)

🧪 Compression Algorithms
Huffman Coding
A lossless compression algorithm that uses variable-length codes based on frequency of characters. Best for text files with repeating patterns.

Run-Length Encoding (RLE)
A simple form of lossless compression where sequences of the same data value are stored as a single value and count.

The system automatically applies the more efficient algorithm, based on compression ratio.

⚙️ Setup Instructions (Run Locally)
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/algorithm-portal.git
cd algorithm-portal
2. Install Dependencies
Frontend

bash
Copy
Edit
cd client
npm install
Backend

bash
Copy
Edit
cd server
npm install
3. Run the App
Start Backend

bash
Copy
Edit
cd server
npm start
Start Frontend

bash
Copy
Edit
cd client
npm start
4. Access the App
Visit: http://localhost:3000 in your browser.

Deployment Link:-
https://vercel.com/russianpinks-projects/algorithm-portal/settings

Deployment Video:-
https://youtu.be/8CkKUFAqfh8?si=XUDUGGe3pODAoJfu

Author :-
Yash Patel
