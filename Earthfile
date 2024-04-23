VERSION --build-auto-skip 0.8
PROJECT electricitymaps/electricitymaps

test-libs:
  BUILD --auto-skip ./libs/db+test

test-projects:
  BUILD --auto-skip ./projects/api+test
  BUILD --auto-skip ./projects/api-docs+test
  BUILD --auto-skip ./projects/landing-page+test

test-all:
  BUILD --auto-skip +test-libs
  BUILD --auto-skip +test-projects