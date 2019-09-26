.PHONY: clean deps build all

all : clean build

clean :
	rm -rf build || true

build :
	mkdir build || true
	cp -r ../definitions/content/*.md build
	cp -r src/* build
	$(MAKE) -C build all
	@echo "The built site is now available in build/_site"

