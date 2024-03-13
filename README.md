# Module 5: Java Profiling

> #### Novrizal Airsyahputra - 2206081780 - Advance Programming B

---

### Reflection

---

**1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?**

The difference between the approach of performance testing w/ JMeter and profiling w/ IntelliJ Profiler:

- JMeter (Performance Testing): Mainly used for load testing, measuring the performance of an application under simulated real-world conditions (performance of an app under various user loads).

- IntelliJ Profiler (Profiling): Focused on analyzing the internal behavior of the application during runtime. It helps identify specific areas of code that may be causing performance issues and gives insights into memory usage, CPU utilization, and method execution times.

---

**2. How does the profiling process help you in identifying and understanding the weak points in your application?**

Here is how the profiling process help me in identifying and understanding the weak point in my app:

Profiling provides detailed information about the execution flow and resource consumption of my application.
By analyzing this data, im able to identify bottlenecks, memory leaks, and inefficient code segments.
Profiling tools like IntelliJ Profiler highlight areas of code where improvements can be made,
helped me to pinpoint and address the performance bottlenecks.

---

**3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?**

Yes, Intellij Profiler is very effective in assisting me to analyze and identify bottlenecks in my app code.
It offers a rich set of features for profiling, including CPU and memory profiling, thread analysis, and more.

---

**4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?**

The main challenges i encounter when conducting performance testing and profiling are:

- Do the optimizing in my code to improve the performance.
- Understanding the profiling result because i have to do some refactoring in my code.

---

**5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?**

Some main benefits i gained from using Intellij Profiler for profiling my app code:

- IntelliJ Profiler provides a detailed and visual representation of the application's runtime behavior.

- Precise identification of performance bottlenecks.

- Insights into memory usage and allocation.

- Thread analysis for concurrency issues.

- Visual representation of method execution times.

---

**6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?**

How i handle situations where the results from profiling w/ Intellij Profiler aren't entirely consistent w/ findings from performance testing using JMeter:

I have to investigate the differences and understand the context of each tool's output.
I think it's possible that JMeter and Profiler focus on different aspects of performance.
I will try to run the tests multiple times, adjusting configurations, and validating results.

---

**7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?**

Strategies I implemented in optimizing app code after analyzing results from performance testing and profiling and how i ensure the changes i make won't affect the app's functionality:

- In my `findStudentWithHighestGPA` method, I tried to enhance the efficiency by implemented the query.
- In my `getAllStudentsWithCourses` method, I tried to reduce the database calls by eliminating them. With using the `studentCourseRepository.findAll()`.
- I tried to do the profiling. With that, i will be able to identify which part of my code that took most time and resources. So, i have to do the performance analysis and do the performance measurements.

Lastly, to ensure the changes i made will not affect the application's functionality is by implementing some unit tests, which i don't right now.

---

### Documentations

Yes, there has been a performance improvement after I tried to optimize them (from the sample time results).
The current code is more effective and efficient.
It can be concluded that the optimization process I tried is successful.

### `/all-student`:
- **Performance testing table results w/ JMeter:**
  ![all-student-request jmeter](https://cdn.discordapp.com/attachments/1111642397248598067/1217426056131248188/before_all_student_request1.png?ex=6603fb5e&is=65f1865e&hm=671e0bdf60ede2f6bfb1ed5a052aaae34c74f9d0f78661ab1e300557cfa822c7&)

- **Performance testing table results w/ Command Line:**
  ![all-student-request command](https://cdn.discordapp.com/attachments/1111642397248598067/1217426056890421288/result1.png?ex=6603fb5e&is=65f1865e&hm=87c2dec0efd59eb9e5284a1c4ac16c2d1b01b2a3554e720ed809a5f51cb6b3fd&)


### `/all-student-name`:
- **Performance testing table results w/ JMeter:**
  ![all-student-name jmeter](https://cdn.discordapp.com/attachments/1111642397248598067/1217426055556632666/before_all_student_name2.png?ex=6603fb5e&is=65f1865e&hm=78d2948defc1331309e9548dce5f8685e8ae8f5d020a9cf16b74d195815414ec&)

- **Performance testing table results w/ Command Line:**
  ![all-student-name command](https://cdn.discordapp.com/attachments/1111642397248598067/1217426057158852608/result2.png?ex=6603fb5e&is=65f1865e&hm=44a63d49ce44d033d2572531e404279c4d2b7e078dfa838354c992cd35cf1a3a&)


### `/highest-gpa`:
- **Performance testing table results w/ JMeter:**
  ![highest-gpa jmeter](https://cdn.discordapp.com/attachments/1111642397248598067/1217426056584368240/before_highest_gpa3.png?ex=6603fb5e&is=65f1865e&hm=3f5afe5d2e5671835a2f3970cecf12f552a1dd3a8e22177951c4d6f8381d96d3&)

- **Performance testing table results w/ Command Line:**
  ![highest-gpa command](https://cdn.discordapp.com/attachments/1111642397248598067/1217426057414840360/result3.png?ex=6603fb5e&is=65f1865e&hm=debb279dfb2ec65011eac0b58392b971a3ace5f17858f857ac623c2ac9756c6b&)

---

### References
1. https://docs.google.com/document/d/16j9SXmwqhCa693w1bFHIo0ShEGCgeUkE/edit
