# SH
BINARY_NAME=fork.sh
DIST=../dist
DIST_DIR=$(DIST)/commons/bin
build:
	mkdir -p $(DIST_DIR)
	cp main.sh $(DIST_DIR)/$(BINARY_NAME) && cp -r fork Dockerfile set_umask.sh $(DIST_DIR)
	chmod +x $(DIST_DIR)/$(BINARY_NAME)