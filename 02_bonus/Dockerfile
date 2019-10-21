# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Dockerfile                                         :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: vsmolii <vsmolii@student.42.fr>            +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/09/07 21:34:50 by vsmolii           #+#    #+#              #
#    Updated: 2019/09/07 21:35:00 by vsmolii          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

# How to build it?
# docker build -t bonus_1 .

# How to run it?
# docker run --rm bonus_1

FROM ubuntu

RUN apt update && apt install -y cowsay && ln -s /usr/games/cowsay /usr/bin/cowsay

ENTRYPOINT ["cowsay"]
