# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Dockerfile                                         :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: vsmolii <vsmolii@student.42.fr>            +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/09/07 20:17:40 by vsmolii           #+#    #+#              #
#    Updated: 2019/09/07 21:08:04 by vsmolii          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

# How to build it?
# "docker build -t ex02 ." - second comand
# "docker run -it --rm -p 3000:3000 ex02" - third
# go to port in Chrome "http://192.168.99.100:3000"

FROM ft-rails:on-build
EXPOSE 3000
CMD ["rails", "s", "-b", "0.0.0.0", "-p", "3000"]
