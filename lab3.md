**Part 1**

- A failure-inducing input for the buggy program, as a JUnit test and any associated code
```@Test
  public void testReversed5() {
    int[] input1 = { 1,2,3,4,5};
    assertArrayEquals(new int[]{5,4,3,2,1 }, ArrayExamples.reversed(input1));
  }
```

- An input that doesn’t induce a failure, as a JUnit test and any associated code
```@Test
  public void testReversed() {
    int[] input1 = { };
    assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
  }
```

- The symptom, as the output of running the tests
  ![Image](lab3output.png)
