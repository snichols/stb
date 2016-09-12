set(stb_headers
	stb_easy_font.h
	stb_image.h
	stb_image_resize.h
	stb_image_write.h
	stb_rect_pack.h
	stb_textedit.h
	stb_truetype.h
)

install(FILES ${stb_headers} DESTINATION include/stb)