# API-Testing-Task

*The URL for the API Tests on Postman:* https://www.postman.com/interstellar-space-909055/workspace/public-workspaces/collection/16463638-2b8cf587-4191-44c1-b324-aaf04e9b4254?action=share&creator=16463638

*Preview on the API htmlextra reporter:* https://htmlpreview.github.io/?https://github.com/shimaaElbateenn/API-Testing-Report/blob/main/Newman%20Summary%20Report.html
Note: Its better to download the report from GitHub so you can be able to scroll and click on elements.


*Documentation*

Cases to validate the functionality and performance of the API:

1. Test Case: Verify API response status code => Assert that the response status code is 200 (OK).
2. Test Case: Verify API response format => Assert that the response content type is "application/json".
3. Test Case: Response time is less than 5000ms => Measures the time taken for one system node to respond to the request of another. It is the time a system takes to reach a specific input until the process is over.
4. Test Case: Check response message => Assert that the first attribute in the response body that called "message" have value "Get Products successfully"
5. Test Case: Number of Products per Page => Assert that the number of products returned in the response matches the specified size.
6. Test Case: Check data type of the response => Assert that the data type of the product has the valid values.
7. Test Case: Check results array inside the response data properties => Assert that the returned product result array (e.g., grade, score, status) is valid and matches the expected values.
8. Test Case: Check the information for response data => Assert that the returned product information (e.g., total, pages) is valid and matches the expected values.
9. Test Case: Schema is valid => Schema Validation to allows you to check if incoming traffic complies with a previously supplied API schema.





