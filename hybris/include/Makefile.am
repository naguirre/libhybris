eglincludedir = $(includedir)/EGL
eglinclude_HEADERS = \
	EGL/egl.h \
	EGL/eglext.h \
	EGL/eglmesaext.h \
	EGL/eglplatform.h

glesincludedir = $(includedir)/GLES
glesinclude_HEADERS = \
	GLES/egl.h \
	GLES/gl.h \
	GLES/glext.h \
	GLES/glplatform.h

gles2includedir = $(includedir)/GLES2
gles2include_HEADERS = \
	GLES2/gl2.h \
	GLES2/gl2ext.h \
	GLES2/gl2platform.h

khrincludedir = $(includedir)/KHR
khrinclude_HEADERS = \
	KHR/khrplatform.h

clincludedir = $(includedir)/CL
clinclude_HEADERS = \
	CL/cl_ext.h \
	CL/cl_gl_ext.h \
	CL/cl_gl.h \
	CL/cl.h \
	CL/cl.hpp \
	CL/cl_platform.h \
	CL/opencl.h

vgincludedir = $(includedir)/VG
vginclude_HEADERS = \
	VG/openvg.h \
	VG/vgext.h \
	VG/vgplatform.h \
	VG/vgu.h

cutilsincludedir = $(includedir)/android/cutils
cutilsinclude_HEADERS = \
	android/cutils/native_handle.h

systemincludedir = $(includedir)/android/system
systeminclude_HEADERS = \
	android/system/window.h \
	android/system/graphics.h

hardwareincludedir = $(includedir)/android/hardware
hardwareinclude_HEADERS = \
	android/hardware/fb.h \
	android/hardware/gralloc.h \
	android/hardware/hardware.h \
	android/hardware/sensors.h \
	android/hardware/lights.h

androidlinuxincludedir = $(includedir)/android/linux
androidlinuxinclude_HEADERS = \
	android/linux/sync.h \
	android/linux/sw_sync.h

syncincludedir = $(includedir)/android/sync
syncinclude_HEADERS = android/sync/sync.h

uiincludedir = $(includedir)/hybris/ui
uiinclude_HEADERS = \
	hybris/ui/ui_compatibility_layer.h

surface_flingerincludedir = $(includedir)/hybris/surface_flinger
surface_flingerinclude_HEADERS = \
	hybris/surface_flinger/surface_flinger_compatibility_layer.h

inputincludedir = $(includedir)/hybris/input
inputinclude_HEADERS = \
	hybris/input/input_stack_compatibility_layer_codes_key.h \
	hybris/input/input_stack_compatibility_layer_flags.h \
	hybris/input/input_stack_compatibility_layer_flags_key.h \
	hybris/input/input_stack_compatibility_layer_flags_motion.h \
	hybris/input/input_stack_compatibility_layer.h

android/version.h: android/version.h.in
	@sed -e "s|\@android_version\@|$(ANDROID_VERSION)|" $<> $@

androidincludedir = $(includedir)/android
androidinclude_HEADERS = \
	android/version.h
