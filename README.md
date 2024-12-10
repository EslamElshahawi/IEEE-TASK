# IEEE-TASK
1_ The combined words function in cpp:
string combineWords(string word1, string word2){
    string result = "";
    int length = max(word1.length(), word2.length());

    for(int i = 0; i < length; i++){
        if(i < word1.length()){
            result += word1[i];
        }
        if(i < word2.length()){
            result += word2[i];
        }
    }
    return result;

}

2_ In OOP, which of the following is the conceptual framework that outlines the characteristics and actions of a particular entity?
  It is the class because it outlines every object's characteristics and methods it can do.

3_ > I use the browser to type https://youtube.com and hit enter. The YouTube page starts loading.
Regarding this statement

= Identify the server, the client and the end-user. Explain the difference between them.
- So the server is the device that hosts the resources for youtube.com which could be one of Google's data centers 
- the client in this context is the web browser on the user's machine 
- the end-user is of course the actual human making those requests and using the client to connect with the server
  
= Mention the HTTP method used in this example and suggest an appropriate status code.
- When you type youtube.com in the browser it requests the page resources with a GET method from the server and as a response in this context the page loads which indicates no errors and maybe a status code of 200 (OK)

4_ Write an SQL query to get the names, phones, and emails of users whose age is greater than or equal to 20
SELECT name, phone, email FROM (the table's name) WHERE age>=20
