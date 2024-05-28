# Classes of Computers

![Classes of Computers](https://github.com/Jaanhvi18/Computer-Architecture-and-OS-Notes/assets/93530844/fdcace03-c48c-4c95-98bb-92f5e4b50126)
*Figure 1.2: A summary of the five mainstream computing classes and their system characteristics. Sales in 2010 included about 1.8 billion PMDs (90% cell phones), 350 million desktop PCs, and 20 million servers. The total number of embedded processors sold was nearly 19 billion. In total, 6.1 billion ARM-technology-based chips were shipped in 2010. Note the wide range in system price for servers and embedded systems, which go from USB keys to network routers. For servers, this range arises from the need for very large-scale multiprocessor systems for high-end transaction processing.*




- ## Personal Mobile Device (PMD)
  - **Price of system**: $100–$1000
  - **Price of microprocessor**: $10–$100
  - **Critical system design issues**:
    - Cost
    - Energy efficiency
    - Media performance
    - Responsiveness
  
  **Additional Notes on PMD**:
  - **Cost Concerns**:
    - Consumer price for PMDs is typically a few hundred dollars --> CHEAP.
    - Cost efficiency becomes important and is achieved through energy efficiency methods:
      - Use of batteries
      - Less expensive packaging materials (e.g., plastic vs. ceramic)
      - Absence of a fan for cooling to limit power consumption
      - Use of Flash memory for storage instead of magnetic disks
  
  - **Applications**:
    - Often web-based and media-oriented (e.g., Google Goggles)
    - Require energy and size efficiency
  
  - **Performance Characteristics**:
    - **Real-time performance**: Segment of the application has an absolute maximum execution time.
      - Example: Processing each video frame within a limited time to maintain responsiveness.
    - **Soft real-time**: Allows occasional misses of time constraints as long as not too many events are missed.
    - Highly dependent on application requirements.
  
  - **Memory and Energy Efficiency**:
    - Minimize memory use to reduce system cost.
    - Optimize memory size to balance cost and performance.
    - Energy efficiency is driven by minimizing battery power and heat dissipation.


- **Desktop**
  - **Price of system**: $300–$2500
  - **Price of microprocessor**: $50–$500
  - **Critical system design issues**:
    - Price-performance
    - Energy 
    - Graphics performance
  
  **Additional Notes on Desktop**:
  - **Cost Concerns**:
    - The desktop computing market is driven by the motivation to optimize price-performance
    - Desktop computing is well characterized in terms of application and benchmarking ***but*** the increasing use of the interactive applications poses new challenges in performance evaluation because:
        - **Latency**: Interactive applications need to minimize the delay between user input and system response. High latency can significantly degrade user experience.
        - **Real-time Performance**: These applications often have to process data in real-time, meaning they must handle input, perform calculations, and render results almost instantaneously.
        - **User Experience**: Performance evaluation now needs to consider subjective measures such as smoothness of interaction, responsiveness, and overall user satisfaction, which are harder to quantify.
        - **Complex Workloads**: Interactive applications may involve complex graphics rendering, real-time data streaming, and high levels of interactivity, all of which add layers of complexity to performance evaluation.

- **Server**
  - 

- **Clusters/Warehouse-Scale Computer**
  - 

- **Embedded**
  - 
