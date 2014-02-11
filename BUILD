[
 { "config": {
    "component": "obabel",
    "licenses": [ "http://www.gnu.org/copyleft/fdl.html",
                  "http://opensource.org/licenses/lgpl-3.0.html",
                  "https://www.gnu.org/licenses/lgpl.html" ]
 } },
 { "cmake": {
    "name": "obabel_cmake",
    "cmake_args": [ "-DEIGEN2_INCLUDE_DIR=$SRC_DIR/third_party/eigen2", "-DBUILD_SHARED=OFF" ],
    "outs": [ "$GEN_DIR/build/src/libopenbabel.a" ]
 } },
 { "cc_library": {
    "name": "obabel",
    "dependencies": [ ":obabel_cmake" ]
 } }
]