FROM %%BASE_IMAGE%%

# Add env
ENV LANG C.UTF-8

# Setup base
RUN apk add --no-cache tzdata chromium-codecs-ffmpeg-extra google-chrome-stable chromium-browser

# Copy data
COPY run.sh /

RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
