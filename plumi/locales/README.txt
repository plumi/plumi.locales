To create/update the pot file, run:
$ i18ndude rebuild-pot --pot locales/plumi.pot --create plumi ../../../plumi.app/ ../../../plumi.content/ ../../../plumi.skin/ other/path/for/plumi/i18n/domain

To update po files (translations) after the pot file has been updated, run:
$ i18ndude sync --pot locales/plumi.pot locales/id/LC_MESSAGES/plumi.po other/po/file.po still/more.po etc.po

