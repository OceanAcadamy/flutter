dart is a synchronous language.
it always finishes code line by line, so if one method or a process takes much time to finish our UI lags or it crashes the app. 
to oversome this we can make the procees or the method to run asynchronously by adding async keyword, which makes the method or the process run in the back ground,
#example
void functionName() async {
//body of the function;
}
