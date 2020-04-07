.PHONY: export

export: stk9900-ananiev.assignment-2.pdf

stk9900-ananiev.assignment-2.pdf: assignment-2.ipynb
	jupyter nbconvert --to=pdf --output=$@ $<
