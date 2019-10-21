# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Dockerfile                                         :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: vsmolii <vsmolii@student.42.fr>            +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/09/07 20:16:32 by vsmolii           #+#    #+#              #
#    Updated: 2019/09/07 20:16:50 by vsmolii          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

FROM alpine

RUN apk update && apk upgrade && apk add vim

ENTRYPOINT vim

# How to build it?
# docker build -t ex00 .

# How to run it?
# docker run --rm -ti ex00
