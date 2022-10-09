idf_component_register(SRCS "dht11.c" "main.c"
                    INCLUDE_DIRS "."
                    EMBED_TXTFILES  "certs/cacert.pem"
                                    "view.html"
                                    "certs/prvtkey.pem")
