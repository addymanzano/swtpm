#
# tests/Makefile.am
#
# For the license, see the LICENSE file in the root directory.
#

check_PROGRAMS =

TESTS = \
	test_init \
	test_getcap \
	test_locality \
	test_hashing \
	test_hashing2 \
	test_volatilestate \
	test_wrongorder \
	test_encrypted_state \
	test_save_load_encrypted_state \
	test_save_load_encrypted_state_2 \
	test_save_load_state \
	test_save_load_state_2 \
	test_migration_key \
	test_migration_key_2 \
	test_tpm_probe \
	\
	test_commandline \
	test_ctrlchannel \
	test_parameters \
	test_resume_volatile \
	test_swtpm_bios \
	\
	test_tpm2_init \
	test_tpm2_getcap \
	test_tpm2_locality \
	test_tpm2_hashing \
	test_tpm2_hashing2 \
	test_tpm2_hashing3 \
	test_tpm2_savestate \
	test_tpm2_wrongorder \
	test_tpm2_probe \
	\
	test_tpm2_swtpm_bios \
	test_tpm2_parameters


if WITH_GNUTLS
TESTS += \
	test_swtpm_cert \
	test_swtpm_setup_create_cert \
	\
	test_tpm2_swtpm_cert \
	test_tpm2_swtpm_setup_create_cert
endif
	
EXTRA_DIST=$(TESTS) \
	swtpm_setup.conf \
	create_certs.sh \
	data/issuercert.pem \
	data/pubek.pem \
	data/signkey.pem \
	data/keyfile.txt \
	data/pwdfile.txt \
	data/migkey1/volatilestate.bin \
	data/tpmstate1/tpm-00.permall \
	data/tpmstate1/tpm-00.volatilestate \
	data/tpmstate1/README \
	data/tpmstate2/tpm-00.permall \
	data/tpmstate2/tpm-00.volatilestate \
	data/tpmstate2/pwdfile.txt \
	data/tpmstate2/README \
	test_cuse \
	test_swtpm_cert
