# **Animated Visualization of Super Bowl Wins**

## **Recap of Data, Goals, and Tasks**  

This project visualizes the cumulative Super Bowl wins of NFL teams from 1967 to 2024 using an animated bar chart. The dataset consists of historical Super Bowl winners, extracted and processed from a CSV file. Source of File is Kaggle https://www.kaggle.com/datasets/timoboz/superbowl-history-1967-2020  

### **Goals**  
- **Informative & Engaging Visualization**: Provide an intuitive way to explore how teams have accumulated Super Bowl wins over time.  
- **Animation for Temporal Trends**: Show how rankings change dynamically, emphasizing dominant teams across different eras.  
- **Branding Elements**: Incorporate team colors and logos to improve recognition and engagement.  

### **Tasks**  
1. **Data Processing**: Convert raw Super Bowl data into a structured format suitable for animation.  
2. **Dynamic Visualization**: Implement an animated horizontal bar chart where bars grow over time based on cumulative wins.  
3. **Enhancing Clarity & Aesthetics**: Use team colors and logos to improve visual appeal and ease of interpretation.  
4. **Evaluation & Refinement**: Gather feedback to assess usability and effectiveness, iterating on design improvements.  


## **Screenshots & Visualization Link**  

If video below doesn't render, here is link to viz: https://drive.google.com/file/d/1FR4XkMLCeSQ_ZaYYWx9a6BbyEVqF5_UZ/view?usp=sharing

<video width="800" height="400" controls>
  <source src="cumulative_superbowl_wins.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## **Key Elements of the Design & Justification**  

### **1. Animated Horizontal Bar Chart**  
- **Justification**: A bar chart is an intuitive way to compare teams, and animation helps illustrate progression over time.  
- **Implementation**: Used Plotly to create frames corresponding to each year, dynamically updating bar lengths.  

### **2. Team Colors & Logos**  
- **Justification**: Helps viewers quickly identify teams and reinforces brand recognition.  
- **Implementation**: Mapped each team to its primary color and displayed logos next to bars in each frame.  

### **3. Interactive Controls**  
- **Justification**: Enables users to control playback, making it easier to analyze specific years.  
- **Implementation**: Added Play/Pause buttons to allow users to engage at their own pace.  

### **4. Clear Axis Labels & Title**  
- **Justification**: Improves readability and understanding of the data.  
- **Implementation**: Used descriptive axis labels and a concise title to communicate the key message.  

## **Final Evaluation Approach**  

### **Procedure**  
- **Recruitment**: Three individuals participated—two sports fans and one with a data visualization background.  
- **Process**: Participants interacted with the visualization and provided feedback based on clarity, usability, and engagement.  
- **Data Collection**: Feedback was gathered via structured questions, focusing on:  
  - Ease of understanding  
  - Effectiveness of animation  
  - Visual appeal  
  - Suggested improvements  

### **Results & Key Takeaways**  

#### **Strengths:**  
- Participants found the animation engaging and informative.  
- Team colors and logos significantly improved identification.  
- The ability to pause and analyze individual years was appreciated.  

#### **Challenges:**  
- Some users found the animation speed too fast to absorb details.  
- A participant suggested adding a hover tooltip to show exact cumulative win counts.  

## **Synthesis & Future Refinements**  

### **What Worked Well**  
**Engaging Animation**: Made trends over time more apparent.  
**Team Branding**: Improved recognition and connection with the data.  
**Interactivity**: Users liked the control over playback.  

### **What to Improve in Future Iterations**  
**Adjustable Animation Speed**: Let users customize playback speed for better accessibility.  
**Hover Tooltips**: Display detailed win counts when hovering over bars.  
**Additional Filters**: Allow users to focus on specific teams or time periods.  

## **Conclusion**  

This project successfully created an engaging and informative animated visualization of Super Bowl wins. The inclusion of team colors, logos, and interactive controls enhanced the user experience. Feedback from evaluators highlighted both strengths and areas for improvement, which can guide future refinements.


