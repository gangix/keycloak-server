FROM quay.io/keycloak/keycloak:22.0.1
ENV KEYCLOAK_ADMIN=${KEYCLOAK_ADMIN}
ENV KEYCLOAK_ADMIN_PASSWORD=${KEYCLOAK_ADMIN_PASSWORD}
RUN /opt/keycloak/bin/kc.sh build
CMD ["start-dev"]