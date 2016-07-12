all: xiaoyongguo.pdf jari_pharm.pdf jari.pdf baoxiali.pdf itinery.pdf

xiaoyongguo.pdf: xiaoyongguo.html main.css Makefile
	prince -v -i xhtml $< -o $@

jari_pharm.pdf: jari_pharm.html main.css Makefile
	prince -v -i xhtml $< -o $@

jari.pdf: jari.html main.css Makefile
	prince -v -i xhtml $< -o $@

baoxiali.pdf: baoxiali.html main.css Makefile
	prince -v -i xhtml $< -o $@

itinery.pdf: itinery.html main.css Makefile
	prince -v -i xhtml $< -o $@


clean:
	rm -rf *.*~ Makefile~ 
