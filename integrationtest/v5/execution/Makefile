BYBIT_TEST_UPDATED=false

test:
	BYBIT_TEST_UPDATED=${BYBIT_TEST_UPDATED} BYBIT_TEST_KEY=${BYBIT_TEST_KEY} BYBIT_TEST_SECRET=${BYBIT_TEST_SECRET} go test github.com/khoakomlem/bybit/v2/integrationtest/v5/execution -v -tags=integrationtestv5execution

test-spec:
	BYBIT_TEST_UPDATED=${BYBIT_TEST_UPDATED} BYBIT_TEST_KEY=${BYBIT_TEST_KEY} BYBIT_TEST_SECRET=${BYBIT_TEST_SECRET} go test github.com/khoakomlem/bybit/v2/integrationtest/v5/execution -v -tags=integrationtestv5execution -run ${BYBIT_TEST_METHOD}

