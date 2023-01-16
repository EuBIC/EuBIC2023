welcome.html: welcome.qmd
	quarto render welcome.qmd

dep:
	scp welcome.html r35:~/WWW/EuBICMSdev2023/ \
	&& scp -r welcome_files r35:~/WWW/EuBICMSdev2023/ \
