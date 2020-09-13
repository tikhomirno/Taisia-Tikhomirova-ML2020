---


---

<h2 id="notes-on-2020-machine-learning-roadmap">Notes on ‘2020 Machine Learning Roadmap’</h2>
<p><em>(<a href="https://www.youtube.com/watch?v=pHiMN_gy9mk&amp;feature=youtu.be">https://www.youtube.com/watch?v=pHiMN_gy9mk&amp;feature=youtu.be</a>)</em></p>
<p><em><strong>PART 0: INTRO</strong></em><br>
<strong>Important links -</strong><br>
<em>Interactive Machine Learning Roadmap (if u are not a fan of 2-hours and a half long videos - better search for needed info here) -</em> <a href="https://www.youtube.com/redirect?q=https%3A%2F%2Fdbourke.link%2Fmlmap&amp;event=video_description&amp;redir_token=QUFFLUhqbDNYWkJtUUtpWnpCUXpPRmJmM0NuVTdTVE1od3xBQ3Jtc0tuS2xYZklZdUtLNXZoNWQ0Q1ZMSURWUlJZbGtTR2dHd0VaNUd4R0RFQVhMZlR0eEJzaC1UTklaS2V1RkUyaUF4MUFCRGZnWW9pTk5PZEFHamZEZER5SlFqZTV0NDBDcWZ1OUlGNHpteFpZUGc2bDNETQ%3D%3D&amp;v=pHiMN_gy9mk">https://dbourke.link/mlmap</a><br>
Honestly - everything u need now is to wonder this map. I tried to take some notes about basic structure of the map, but honestly - this map in the best conspect.</p>
<p><em>Machine Learning Roadmap Resources</em> - <a href="https://www.youtube.com/redirect?q=https%3A%2F%2Fgithub.com%2Fmrdbourke%2Fmachine-learning-roadmap&amp;event=video_description&amp;redir_token=QUFFLUhqbTNHRE9lNko3YWk1d3Z6OTU2S0lZa2hLdDFBd3xBQ3Jtc0trMnE0SUNJZ0RwdW1JbmEtN0w0WmdKbEF2SDFIWWZscGpKNGVVWG5VQUllODAwU0FNM2t2SzZtQ2luMGVMUDdTUk1hNnRpUWd2MmFlT3J0eW1Qa3AzTWN0elhXc2tySFhHc0Z3UEZ0N2tjdHd3RGhWSQ%3D%3D&amp;v=pHiMN_gy9mk">https://github.com/mrdbourke/machine-…</a><br>
<em>Learn machine learning (via the course I teach)</em> - <a href="https://www.youtube.com/redirect?q=https%3A%2F%2Fdbourke.link%2Fmlcourse&amp;event=video_description&amp;redir_token=QUFFLUhqbHVvNlhsaGFDVHQ5RHc0dHAzNzBGX3JneHFRZ3xBQ3Jtc0trcFhubHowbUQ2cXZTN3YtaFBfaTREM2JLYjRpYXl4OGNzLTA1LWs1cXpnU2pHa0FEVFRFVFJyRlVVRFc1UDJ0MWJDSU5XVFlZRnJyekltTndaY0hFMnV0R2tueVB0cFNnTkhwMmFTX3pUYVlqLThqWQ%3D%3D&amp;v=pHiMN_gy9mk">https://dbourke.link/mlcourse</a></p>
<p>What is ML?<br>
ML - turning data into numbers and finding patterns in those numbers.</p>
<p>Machine learning (2.0) vs. traditional programming(1.0)<br>
2.0 needs 1.0, but 1.0 does not need 2.0.</p>
<p>1.0 = input - instructions - ideal output<br>
2.0 = input - ideal output - instructions</p>
<p><strong>We need ML</strong></p>
<ul>
<li>when we do not know all the RULES (instructions) and our task is to figure it out</li>
<li>when environments continually change</li>
<li>discover insights within large collections of data</li>
</ul>
<p><strong>PART 1: Machine Learning Problems</strong></p>
<p><em>Categories of learning:</em></p>
<ul>
<li>supervised</li>
<li>unsupervised</li>
<li>transfer  (take working ml patterns and apply then to ur data)</li>
<li>reinforcement</li>
</ul>
<p><em>U should go to roadmap (link upstairs) to lear more about each one!</em></p>
<p><em>Problem domains:</em></p>
<ul>
<li>
<p>classification</p>
<ul>
<li>
<p>example problems</p>
<ul>
<li>binary</li>
<li>multy-class</li>
<li>multy-label</li>
</ul>
</li>
<li>
<p>evaluation metrics</p>
<ul>
<li>confusion matrix</li>
<li>остальное в роадмэп</li>
</ul>
</li>
</ul>
</li>
<li>
<p>regression</p>
<ul>
<li>rˆ2</li>
<li>mse (mean square error)</li>
<li>mae (mean absolute error)</li>
</ul>
</li>
<li>
<p>clustering</p>
</li>
<li>
<p>dimensionality reduction (игнорируем ненужные категории в дате)</p>
</li>
<li>
<p>seq2seq (translation for example)</p>
</li>
</ul>
<p><em>U should go to roadmap (link upstairs) to lear more about each one! x2</em></p>
<p><strong>PART 2: Machine Learning Process</strong></p>
<p>Steps in ML project:</p>
<ul>
<li>
<p>data collection</p>
<ul>
<li>
<p>understand where u would search for data, is it public, how to collect it?</p>
</li>
<li>
<p>what type of data?</p>
<ul>
<li>
<p>nominal</p>
</li>
<li>
<p>numerical</p>
</li>
<li>
<p>ordinal</p>
</li>
<li>
<p>time series</p>
</li>
<li>
<p>unstructured data (seq2seq)</p>
</li>
</ul>
</li>
</ul>
</li>
<li>
<p>data preparation</p>
<ul>
<li>
<p>EDA (exploratory data anal)</p>
</li>
<li>
<p>data preprocessing</p>
<ul>
<li>f. imputation</li>
<li>f.encoding</li>
<li>f.normalization</li>
<li>f.engineering</li>
<li>f.selection</li>
<li>dealing with imbalances</li>
</ul>
</li>
<li>
<p>data splitting</p>
<ul>
<li>
<p>training (70-80) (sklearn to import some ml models)</p>
</li>
<li>
<p>validation (10-15)</p>
</li>
<li>
<p>test set (10-15)</p>
</li>
</ul>
</li>
</ul>
</li>
<li>
<p>train model on data</p>
<ul>
<li>choose an algorithm (look P1)</li>
<li>type of learning</li>
<li>underfitting</li>
<li>overfitting</li>
</ul>
</li>
<li>
<p>analysis/evaluation</p>
<ul>
<li>evaluation metrix</li>
<li>feaure importance</li>
<li>training</li>
<li>compare to other models</li>
<li>what does ml model get wrong</li>
<li>bias</li>
</ul>
</li>
<li>
<p>serve model</p>
</li>
<li>
<p>retrain model (when necessary)</p>
</li>
</ul>
<p><em>U should go to roadmap (link upstairs) to lear more about each one! x3</em></p>
<p><strong>PART 3: Machine Learning Tools</strong></p>
<ul>
<li>
<p>libraries (py)</p>
<ul>
<li>scikit-learn</li>
<li>pytorch</li>
<li>tensorflow (pretty same as pytorch)</li>
<li>onnx (for c++ too)</li>
</ul>
</li>
<li>
<p>toolbox</p>
<ul>
<li>
<p>pretrand models</p>
<ul>
<li>tensorflow hub</li>
<li>pytorch hub</li>
<li>huggingface transformers (nat language )</li>
<li>detectron2</li>
</ul>
</li>
<li>
<p>experiment tracking</p>
</li>
<li>
<p>data tracking (DVC)</p>
</li>
<li>
<p>cloud compute services</p>
</li>
<li>
<p>hardware</p>
</li>
<li>
<p>AutoML</p>
</li>
<li>
<p>Explainability</p>
</li>
<li>
<p>…</p>
</li>
</ul>
</li>
</ul>
<p><strong>PART 4: Machine Learning Mathematics</strong></p>
<ul>
<li>линейная алгебра</li>
<li>матрицы</li>
<li>многомерный анализ</li>
<li>априорная вероятность</li>
<li>probability (kak eto po-russki?)</li>
<li>оптимизация</li>
<li>chain rule (??)<br>
<a href="https://mml-book.github.io/">https://mml-book.github.io/</a><br>
<a href="https://www.deeplearningbook.org/">https://www.deeplearningbook.org/</a></li>
</ul>
<p><strong>PART 5: Machine Learning Resources</strong></p>
<p>Лучше всего зайти на карту и потыкать, что конкретно нужно!</p>
<p>Внутри карты есть сегменты по:</p>
<ul>
<li>коду</li>
<li>концепту и процессу МО</li>
<li>математике</li>
<li>тому, как учиться :)</li>
</ul>
<p>Подборки:</p>
<ul>
<li>книг</li>
<li>облачных сервисов</li>
<li>сводов правил и чек-листов</li>
<li>сетов даты</li>
</ul>

