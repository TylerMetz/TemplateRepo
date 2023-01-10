# we don’t want to use relative paths, so we set these variables
PROJECT_DIR=/Users/tylermetz/git/TemplateRepo
SRC_DIR=$(PROJECT_DIR)/src
TEST_DIR=$(PROJECT_DIR)/t
# specify where the source code and includes are located
INCLUDE_DIRS=$(SRC_DIR)/code
SRC_DIRS=$(SRC_DIR)/code

# specify where the test code is located
TEST_SRC_DIRS = $(TEST_DIR)

# what to call the test binary
TEST_TARGET=example #change here

# where the cpputest library is located
CPPUTEST_HOME=$(PROJECT_DIR)/cpputest

# run MakefileWorker.mk with the variables defined here
include $(CPPUTEST_HOME)/build/MakefileWorker.mk
