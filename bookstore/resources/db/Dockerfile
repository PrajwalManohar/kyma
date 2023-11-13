# Use the capbuilder for the first stage build
FROM prajwalmanohar/bscapui5tools as capbuild
#Base version
ENV VERSION 1.0.0
# Create app directory, in which the CAP service is built
WORKDIR /db
# build app
RUN ["cds", "build"]