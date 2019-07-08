txt = Hello World
v1 = $(txt)

value=hi

VARIABLE=hello

# 只有在该变量为空时才设置值。
VARIABLE ?= $(value)

# 在定义时扩展。
VARIABLE := $(value)

# 将值追加到变量的尾端。
VARIABLE += $(value)

# 在执行时扩展，允许递归扩展。
VARIABLE = $(value)


echo-variable:
	@echo $(VARIABLE)

test:
	@echo $(txt)
echo:
	@echo $(v1)

echo-home:
	# using $ to escape the $HOME
	@echo $$HOME

%o:%c
	@$(CC) -o $@ $<; echo ">>> "$<

make-echo-home:
	@$(MAKE) echo-home