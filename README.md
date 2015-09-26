# LogError
Error in Eclipse with P2D


Exception in thread "AWT-EventQueue-1" javax.media.opengl.GLException: Caught RuntimeException: Framebuffer objects are not supported by this hardware (or driver) Read http://wiki.processing.org/w/OpenGL_Issues for help. on thread AWT-EventQueue-1
	at javax.media.opengl.GLException.newGLException(GLException.java:75)
	at jogamp.opengl.GLDrawableHelper.invokeGLImpl(GLDrawableHelper.java:1311)
	at jogamp.opengl.GLDrawableHelper.invokeGL(GLDrawableHelper.java:1131)
	at javax.media.opengl.awt.GLCanvas$11.run(GLCanvas.java:1394)
	at javax.media.opengl.Threading.invoke(Threading.java:223)
	at javax.media.opengl.awt.GLCanvas.display(GLCanvas.java:525)
	at javax.media.opengl.awt.GLCanvas.paint(GLCanvas.java:579)
	at sun.awt.RepaintArea.paintComponent(Unknown Source)
	at sun.awt.RepaintArea.paint(Unknown Source)
	at sun.awt.windows.WComponentPeer.handleEvent(Unknown Source)
	at java.awt.Component.dispatchEventImpl(Unknown Source)
	at java.awt.Component.dispatchEvent(Unknown Source)
	at java.awt.EventQueue.dispatchEventImpl(Unknown Source)
	at java.awt.EventQueue.access$500(Unknown Source)
	at java.awt.EventQueue$3.run(Unknown Source)
	at java.awt.EventQueue$3.run(Unknown Source)
	at java.security.AccessController.doPrivileged(Native Method)
	at java.security.ProtectionDomain$JavaSecurityAccessImpl.doIntersectionPrivilege(Unknown Source)
	at java.security.ProtectionDomain$JavaSecurityAccessImpl.doIntersectionPrivilege(Unknown Source)
	at java.awt.EventQueue$4.run(Unknown Source)
	at java.awt.EventQueue$4.run(Unknown Source)
	at java.security.AccessController.doPrivileged(Native Method)
	at java.security.ProtectionDomain$JavaSecurityAccessImpl.doIntersectionPrivilege(Unknown Source)
	at java.awt.EventQueue.dispatchEvent(Unknown Source)
	at java.awt.EventDispatchThread.pumpOneEventForFilters(Unknown Source)
	at java.awt.EventDispatchThread.pumpEventsForFilter(Unknown Source)
	at java.awt.EventDispatchThread.pumpEventsForHierarchy(Unknown Source)
	at java.awt.EventDispatchThread.pumpEvents(Unknown Source)
	at java.awt.EventDispatchThread.pumpEvents(Unknown Source)
	at java.awt.EventDispatchThread.run(Unknown Source)
Caused by: java.lang.RuntimeException: Framebuffer objects are not supported by this hardware (or driver) Read http://wiki.processing.org/w/OpenGL_Issues for help.
	at processing.opengl.PJOGL$PGLListener.init(PJOGL.java:890)
	at jogamp.opengl.GLDrawableHelper.init(GLDrawableHelper.java:640)
	at jogamp.opengl.GLDrawableHelper.init(GLDrawableHelper.java:662)
	at javax.media.opengl.awt.GLCanvas$9.run(GLCanvas.java:1366)
	at jogamp.opengl.GLDrawableHelper.invokeGLImpl(GLDrawableHelper.java:1275)
	... 28 more
Framebuffer error (framebuffer unsupported), rendering will probably not work as expected Read http://wiki.processing.org/w/OpenGL_Issues for help.
OpenGL error 1280 at bot beginDraw(): invalid enumerant
Unfolding Map v0.9.7 (UCSD edition)
Using OpenGLMapDisplay with processing.opengl.PGraphics2D
Using OpenGLMapDisplay with processing.opengl.PGraphics2D
OpenGL error 1286 at top endDraw(): invalid framebuffer operation
#
# A fatal error has been detected by the Java Runtime Environment:
#
#  EXCEPTION_ACCESS_VIOLATION (0xc0000005) at pc=0x17a792cd, pid=1796, tid=3600
#
# JRE version: Java(TM) SE Runtime Environment (8.0_60-b27) (build 1.8.0_60-b27)
# Java VM: Java HotSpot(TM) Client VM (25.60-b23 mixed mode, sharing windows-x86 )
# Problematic frame:
# C  [ig4icd32.dll+0x2092cd]
#
# Failed to write core dump. Minidumps are not enabled by default on client versions of Windows
#
# An error report file with more information is saved as:
# D:\Corsi\Java_Coursera\workspace\UCSDUnfoldingMaps\build\hs_err_pid1796.log
#
# If you would like to submit a bug report, please visit:
#   http://bugreport.java.com/bugreport/crash.jsp
# The crash happened outside the Java Virtual Machine in native code.
# See problematic frame for where to report the bug.
#

