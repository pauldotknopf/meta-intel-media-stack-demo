FROM gmacario/build-yocto

RUN echo "jenkins ALL=(ALL) NOPASSWD: ALL" | sudo tee -a /etc/sudoers

RUN sudo git config --system user.email "nobody@nobody.com"
RUN sudo git config --system user.name "No Body"