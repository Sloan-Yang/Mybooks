The best way to read book is use marker to convert pdf to markdown format


TORCH_DEVICE=cuda marker book1/ \
  --output_dir ./book1/out \
  --use_llm \
  --force_ocr \
  --redo_inline_math \
  --strip_existing_ocr \
  --paginate_output


llm need we provide api.


TORCH_DEVICE=cuda marker FontDiffuser/ \
  --output_dir ./FontDiffuser/out \
  --force_ocr \
  --redo_inline_math \
  --strip_existing_ocr \
  --paginate_output


CUDA_VISIBLE_DEVICES=1 TORCH_DEVICE=cuda marker 反抗者\            
                              --output_dir ./反抗者/out \
                                  --force_ocr \
                                  --redo_inline_math \
                                  --strip_existing_ocr \
                                  --paginate_output

CUDA_VISIBLE_DEVICES=1 TORCH_DEVICE=cuda marker "经营未来" \
  --output_dir "./经营未来/out" \
  --force_ocr \
  --redo_inline_math \
  --strip_existing_ocr \
  --paginate_output


CUDA_VISIBLE_DEVICES=1 TORCH_DEVICE=cuda marker "作为意志和表象的世界" \
  --output_dir "./作为意志和表象的世界/out" \
  --force_ocr \
  --redo_inline_math \
  --strip_existing_ocr \
  --paginate_output

