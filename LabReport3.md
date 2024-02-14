# Lab Report 3
# Part 1 - Bugs
## 1. Failure-Inducing Input for `reverseInPlace`
```
@Test
public void testReverseInPlace2() {
    int[] input1 = {11, 1, 2, 20};
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{20, 2, 1, 11}, input1);
}
```

## 2. An input that doesn't induce a failure for `reverseInPlace`:
```
@Test 
public void testReverseInPlace() {
    int[] input1 = { 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
}
```

## 3. The symptom:
