.PHONY: clean deps build all

all : clean deps build

clean :
	rm -rf _site || true

deps :
	bundle --path vendor/bundle

build :
	bundle exec jekyll build
	@echo "The built site is now available in _site"

