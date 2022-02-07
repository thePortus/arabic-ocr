# arabic-ocr

*A Digital Humanities Exercise: Batch converting folders of Arabic PDFs to plaintext files.*

[David J. Thomas](mailto:dave.a.base@gmail.com), [thePort.us](http://thePort.us)<br />

<a alt="Binder" href="https://mybinder.org/v2/gh/thePortus/arabic-ocr/HEAD" target="_blank"><img src="https://mybinder.org/badge.svg" /><a/>

### Run In Your Broswer

This exercise uses a Jupyter Notebook to demonstrates converting Arabic PDFs to plain text files. Rather than install locally, see this notebook in action in your browser at [MyBinder](https://mybinder.org/v2/gh/thePortus/arabic-ocr/HEAD). Once the server is launched (it takes awhile, ignore any warnings), choose `acabic-ocr.ipynb` from the navigation menu on the left. To run code, click your mouse inside a cell of code, then click the play button to run that cell.

### To Install Locally

Open your prompt, navigate to your desire parent folder and enter

```
git clone https://github.com/thePortus/arabic-ocr.git
cd arabic-ocr
pip install -r requirements.txt
```

You also need to install `poppler`, a software library that powers the PDF reader.

* On OSX machines, open your terminal and enter `brew install poppler`
* For Linux machines, open your terminal and enter `sudo apt-get install poppler-utils`.
* Windows is a bit harder as `poppler` wasn't originally meant for it, but you can find a Windows downloadable installer [here](https://blog.alivate.com.au/poppler-windows/) along with some discussion from a forum about how to set it up [here](https://stackoverflow.com/questions/18381713/how-to-install-poppler-on-windows).

To launch the notebook from your terminal just enter `jupyter notebook`

Once the interface launches in your webbrowser, select `arabic-ocr.ipynb` and get started.
