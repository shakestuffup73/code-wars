<h1>Javascript Coding Practice from CodeWars, LeetCode and Discord</h1>
<h4><i>This will be a workspace to practice Javascript coding challenges. I'll include the original word problem prompt and provided test cases, as well as my solution(s) for having solved them.</i></h4>
<h4>Challenge Problem 1: Factorial Using Recursion</h4>
<h5>
function factorial(){
  <br>
    // This function returns the factorial of a given number.
  <br>
    // You must set the parameters of the function yourself
  <br>
    //  The input will be a positive integer greater than zero
  <br>
}
<br>
<br>
Test Cases:
<br>
<br>
mocha.setup('bdd');

const expect = chai.expect;

describe('factorial', ()=>{
  <br>
    it('should accurately calculate factorials', ()=>{
      <br>
        expect(factorial(3)).to.equal(6);
        expect(factorial(5)).to.equal(120);
        <br>
    });
    <br>
})

mocha.run()
</h4>

