# spam-email-classifier-using-MNB-classifier
A machine learning model that predicts whether the mail is spam or ham with 98%+ accuracy made using Multinomial Naive Bayes Classifier
<br>
TEST CASES:

Test Case 1: Ham Email
<br>
Input: "Hey, how are you doing?"<br>
Expected Output: "Given email is not spam"<br>
Test Case 2: Spam Email<br>

Input: "Click here to claim your prize!"<br>
Expected Output: "Given email is spam"<br>
Test Case 3: Neutral Email<br>
<br>
Input: "Meeting reminder: Tomorrow at 10 AM"<br>
Expected Output: "Given email is not spam"<br>
Test Case 4: Empty Email<br>
<br>
Input: ""<br>
Expected Output: "Given email is not spam" (assuming an empty email is considered not spam)<br>
Test Case 5: Email with Numbers<br>
<br>
Input: "Buy now! Offer ends in 3 days."<br>
Expected Output: "Given email is spam" (assuming emails with numbers are often spam)<br>
Test Case 6: Email with Special Characters<br>
<br>
Input: "𝑆𝑝𝑒𝑐𝑖𝑎𝑙 𝐷𝑖𝑠𝑐𝑜𝑢𝑛𝑡<br>
SpecialDiscount"<br>
Expected Output: "Given email is spam" (assuming emails with excessive special characters are spam)<br>
Test Case 7: Email with Mixed Case<br>

Input: "cLiCk HeRe To ClAiM YoUr PrIzE!"<br>
Expected Output: "Given email is spam" (assuming emails with mixed case are often spam)<br>
Test Case 8: Email with URLs<br>

Input: "Visit our website at www.example.com"<br>
Expected Output: "Given email is spam" (assuming emails with URLs are often spam)<br>
Test Case 9: Email with Uncommon Words<br>

Input: "Supercalifragilisticexpialidocious"<br>
Expected Output: "Given email is not spam" (assuming uncommon words are not indicative of spam)<br>



