FROM faddat/sos-lite

# Add seeds and such after doing gaia.
# I will prototype the rest of this on gaia.
RUN echo voter > /etc/hostname && \
		pacman -Syyu --noconfirm docker-compose zerotier-one
#		echo "docker run alice/voter" >> /usr/local/bin/firstboot.sh
# TODO: docker-compose
