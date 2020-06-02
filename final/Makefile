.PHONY: export

export: stk9900.final.pdf

stk9900.final.pdf: stk9900-final.ipynb
	jupyter nbconvert --to=pdf --output=$@ $<
