

## Notes on '2020 Machine Learning Roadmap' 
*(https://www.youtube.com/watch?v=pHiMN_gy9mk&feature=youtu.be)*

***PART 0: INTRO***
**Important links -** 
*Interactive Machine Learning Roadmap (if u are not a fan of 2-hours and a half long videos - better search for needed info here) -* [https://dbourke.link/mlmap](https://www.youtube.com/redirect?q=https%3A%2F%2Fdbourke.link%2Fmlmap&event=video_description&redir_token=QUFFLUhqbDNYWkJtUUtpWnpCUXpPRmJmM0NuVTdTVE1od3xBQ3Jtc0tuS2xYZklZdUtLNXZoNWQ0Q1ZMSURWUlJZbGtTR2dHd0VaNUd4R0RFQVhMZlR0eEJzaC1UTklaS2V1RkUyaUF4MUFCRGZnWW9pTk5PZEFHamZEZER5SlFqZTV0NDBDcWZ1OUlGNHpteFpZUGc2bDNETQ%3D%3D&v=pHiMN_gy9mk)
Honestly - everything u need now is to wonder this map. I tried to take some notes about basic structure of the map, but honestly - this map in the best conspect. 

*Machine Learning Roadmap Resources* - [https://github.com/mrdbourke/machine-...](https://www.youtube.com/redirect?q=https%3A%2F%2Fgithub.com%2Fmrdbourke%2Fmachine-learning-roadmap&event=video_description&redir_token=QUFFLUhqbTNHRE9lNko3YWk1d3Z6OTU2S0lZa2hLdDFBd3xBQ3Jtc0trMnE0SUNJZ0RwdW1JbmEtN0w0WmdKbEF2SDFIWWZscGpKNGVVWG5VQUllODAwU0FNM2t2SzZtQ2luMGVMUDdTUk1hNnRpUWd2MmFlT3J0eW1Qa3AzTWN0elhXc2tySFhHc0Z3UEZ0N2tjdHd3RGhWSQ%3D%3D&v=pHiMN_gy9mk)
*Learn machine learning (via the course I teach)* - [https://dbourke.link/mlcourse](https://www.youtube.com/redirect?q=https%3A%2F%2Fdbourke.link%2Fmlcourse&event=video_description&redir_token=QUFFLUhqbHVvNlhsaGFDVHQ5RHc0dHAzNzBGX3JneHFRZ3xBQ3Jtc0trcFhubHowbUQ2cXZTN3YtaFBfaTREM2JLYjRpYXl4OGNzLTA1LWs1cXpnU2pHa0FEVFRFVFJyRlVVRFc1UDJ0MWJDSU5XVFlZRnJyekltTndaY0hFMnV0R2tueVB0cFNnTkhwMmFTX3pUYVlqLThqWQ%3D%3D&v=pHiMN_gy9mk)

What is ML?
ML - turning data into numbers and finding patterns in those numbers.

Machine learning (2.0) vs. traditional programming(1.0)
2.0 needs 1.0, but 1.0 does not need 2.0. 

1.0 = input - instructions - ideal output
2.0 = input - ideal output - instructions

**We need ML**
- when we do not know all the RULES (instructions) and our task is to figure it out
- when environments continually change 
- discover insights within large collections of data

**PART 1: Machine Learning Problems**

*Categories of learning:*
- supervised 
- unsupervised 
- transfer  (take working ml patterns and apply then to ur data)
- reinforcement 

*U should go to roadmap (link upstairs) to lear more about each one!* 

*Problem domains:*

- classification
	- example problems
		- 	binary
		- multy-class
		-  multy-label
	- evaluation metrics 
	
		- confusion matrix 
		- остальное в роадмэп
- regression 
	
	- rˆ2
	- mse (mean square error)
	- mae (mean absolute error)
- clustering
- dimensionality reduction (игнорируем ненужные категории в дате)
- seq2seq (translation for example)

*U should go to roadmap (link upstairs) to lear more about each one! x2* 



**PART 2: Machine Learning Process**

Steps in ML project:

- data collection
	
	- understand where u would search for data, is it public, how to collect it?
	- what type of data? 
		
		- nominal
		
		- numerical
		-  ordinal 
		- time series 
		- unstructured data (seq2seq)
		
- data preparation 
	
	- EDA (exploratory data anal)
	- data preprocessing 
		
		- f. imputation
		- f.encoding
		- f.normalization
		- f.engineering
		- f.selection
		- dealing with imbalances 
	- data splitting 
		
		- training (70-80) (sklearn to import some ml models)
			
				 
		- validation (10-15)
		- test set (10-15)
			 
	
- train model on data
	
	- choose an algorithm (look P1)	
	- type of learning 
	- underfitting 
	- overfitting 
	
- analysis/evaluation
	
	- evaluation metrix
	- feaure importance 
	- training 
	- compare to other models
	- what does ml model get wrong
	- bias
	
- serve model

- retrain model (when necessary)

*U should go to roadmap (link upstairs) to lear more about each one! x3* 

**PART 3: Machine Learning Tools**

- libraries (py)

	-	scikit-learn
	-	pytorch 
	-	tensorflow (pretty same as pytorch)
	-	onnx (for c++ too)
- toolbox
	- pretrand models 

		- tensorflow hub
		- pytorch hub
		- huggingface transformers (nat language )
		- detectron2
	- experiment tracking
	- data tracking (DVC)
	- cloud compute services
	- hardware
	- AutoML
	- Explainability
	- ... 
	
**PART 4: Machine Learning Mathematics**

- линейная алгебра 
- матрицы
- многомерный анализ 
- априорная вероятность 
- probability (kak eto po-russki?)
- оптимизация 
- chain rule (??)
https://mml-book.github.io/
https://www.deeplearningbook.org/

**PART 5: Machine Learning Resources**
 
Лучше всего зайти на карту и потыкать, что конкретно нужно! 

Внутри карты есть сегменты по:

- коду
- концепту и процессу МО
- математике
- тому, как учиться :)

Подборки: 

- книг 
- облачных сервисов 
- сводов правил и чек-листов 
- сетов даты 




