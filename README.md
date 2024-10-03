# **VeriChain** - Document Verification System using AI and Blockchain

## **Vision**
VeriChain aims to revolutionize document verification by leveraging AI for text extraction and blockchain for secure, tamper-proof data storage. The system automates the identity verification process, improving efficiency, security, and scalability for entry and exit management systems.

## **Features**
- **AI-powered OCR**: Uses the Gemini API for Optical Character Recognition (OCR) to extract text from document images.
- **Blockchain Security**: Employs the NeoX blockchain to store document data hashes using the SHA-256 algorithm, ensuring immutability and tamper-proof storage.
- **Entry-Exit Automation**: Automatically detects users upon entry or exit using the verified identity card, enabling seamless, touchless access control.
- **Web-Based Interface**: The front-end is built using HTML5, Tailwind CSS, JavaScript, and Bootstrap, ensuring a modern, responsive design.
- **Privacy Protection**: Only the hash of the document information is stored on the blockchain, ensuring user privacy while maintaining document authenticity.
- **Scalability**: The system can be expanded to support multiple document types and identities beyond the initial implementation of the Rise In X NeoX identity card.

## **Project Structure**
```
.
├── .env
├── app.py
├── requirements.txt
├── README.md
├── document_verification.db
├── static/
│   ├── tailwind.min.css
│   ├── main.css
│   ├── favicon.jpg
│   ├── bootstrap.min.css
├── templates/
│   ├── index.html
│   ├── result.html
│   ├── upload.html
│   ├── verify.html
├── uploads/
```

## **How It Works**
1. **Document Capture**: The user captures an image of their document (currently using the Rise In X NeoX identity card).
2. **OCR Process**: The AI-powered OCR extracts text from the document.
3. **Hash Generation**: The SHA-256 algorithm generates a hash from the extracted text.
4. **Blockchain Storage**: The generated hash is stored securely on the NeoX blockchain, ensuring tamper-proof storage.
5. **Automated Detection**: When the user enters or leaves the location again, the system automatically detects the card and verifies it against the stored hash.

## **ScrenShots**
![Image 1](./images/img1.png)
![Image 2](./images/img2.png)
![Image 3](./images/img3.png)

## **Technologies Used**
- **AI Gemini API**: For Optical Character Recognition (OCR) to extract text from document images.
- **NeoX Blockchain**: Ensures secure, decentralized storage of document information hashes.
- **HTML5**: For structuring the web application.
- **Tailwind CSS**: For responsive and modern design.
- **JavaScript**: For handling the OCR process, hash generation, and blockchain interactions.
- **Bootstrap**: Provides a sleek, responsive user interface.

## **Deployment**
You can Host it on Localhost
using the given commands

To deploy the application locally:

1. Clone the repository and install requirements:
   ```bash
   git clone https://github.com/inder-26/verichain.git
   cd verichain
   pip install -r requirements.txt
   ```
2. Run `app.py` using python to interact with the system.
   ```bash
   python app.py
   ```
3. Open `http://127.0.0.1:5000` after running `app.py`

---

### **Future Enhancements**
- **Multi-Document Support**: Extend the system to handle various types of documents, such as passports, driver's licenses, etc.
- **Mobile App**: Build a mobile application to allow users to scan and verify documents on the go.
- **Advanced AI Integration**: Improve OCR accuracy by integrating more advanced AI models.
- **Global Blockchain Integration**: Add support for multiple blockchain networks to enhance decentralization and security.

---

### **Contributing**
We welcome contributions! If you'd like to improve VeriChain, feel free to fork the repository, make your changes, and submit a pull request.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Create a pull request

---

### **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

### **Contact**
For questions or inquiries, please reach out at [inder26112004@gmail.com](mailto:inder26112004@gmail.com).
