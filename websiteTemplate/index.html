<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <button  onclick="getLocation">SOS</button>
    <script>
     const getLocation = () => {
    // get user location with IP address using ipapi
    fetch("https://ipapi.co/json/")
        .then((response) => response.json())
        .then((data) => {
            const des = document.querySelector("p");
            des.innerHTML = `Latitude: ${data.latitude}, Longitude: ${data.longitude}`;
        })
        .catch((error) => {
            console.error('Error fetching location:', error);
        });
};

         </script>
<?php

// Function to send an email with a JSON file attachment using MIME
function sendEmailWithAttachment($filePath, $recipientEmail) {
    $boundary = md5(uniqid(rand(), true));
    
    // Sender information
    $from = 'oms.cse22@sbjit.edu.in'; // Your Gmail email address
    $subject = 'JSON File Attachment';
    
    // Additional headers
    $headers  = "From: $from\r\n";
    $headers .= "MIME-Version: 1.0\r\n";
    $headers .= "Content-Type: multipart/mixed; boundary=\"$boundary\"\r\n";
    
    // Message body
    $message = "--$boundary\r\n";
    $message .= "Content-Type: text/plain; charset=\"UTF-8\"\r\n";
    $message .= "Content-Transfer-Encoding: 7bit\r\n\r\n";
    $message .= "Please find the attached JSON file.\r\n\r\n";
    
    // Attachment
    $fileContent = file_get_contents($filePath);
    $encodedFileContent = chunk_split(base64_encode($fileContent));
    
    $message .= "--$boundary\r\n";
    $message .= "Content-Type: application/json; name=\"data.json\"\r\n";
    $message .= "Content-Disposition: attachment; filename=\"data.json\"\r\n";
    $message .= "Content-Transfer-Encoding: base64\r\n\r\n";
    $message .= $encodedFileContent . "\r\n\r\n";
    $message .= "--$boundary--";
    
    // Send the email
    return mail($recipientEmail, $subject, $message, $headers);
}

// Example usage
$jsonFilePath = './slide1.jpg'; // Replace with your JSON file path
$recipientEmail = 'udayg.cse22@sbjit.edu.in'; // Replace with the recipient's email address

$result = sendEmailWithAttachment($jsonFilePath, $recipientEmail);

if ($result) {
    echo 'Email sent successfully!';
} else {
    echo 'Error sending email.';
}
?>

</body>
</html>


