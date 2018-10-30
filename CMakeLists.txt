project(QrCodeGen LANGUAGES CXX)

set(LIBSOURCES
	BitBuffer.cpp
	QrCode.cpp
	QrSegment.cpp
)

set(LIBHEADERS
	BitBuffer.hpp
	QrCode.hpp
	QrSegment.hpp
)

add_library(QrCodeGen-static STATIC ${LIBSOURCES} ${LIBHEADERS})
