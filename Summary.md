---
tags:
  - summary
  - uni
---
## University of Geneva - Computer Science

### 3rd Year Courses - Autumn Semester:
- [[Artificial Intelligence|Artificial Intelligence (13X005)]]
- [[Parallelism|Parallelism (13X007)]]
- [[Computer Networks|Computer Networks (13X009)]]
- [[Concurrent Systems|Concurrent Systems (13X012)]]

### 3rd Year Courses - Spring Semester:
- [[Bachelor's Project]]

## Stats
```dataviewjs
const tagPages = dv.pages('#uni'); 

var labels = [], 
	wordCount = []; 
	
tagPages.forEach(note => {
	labels.push(note.file.name);
	wordCount.push(note.file.size); 
}); 
const chartData = {  
	type: 'bar', 
	data: { 
		labels: labels, 
		datasets: [{ 
			label: 'File Size', 
			data: wordCount 
		}] 
	}
} 
window.renderChart(chartData, this.container);
```
