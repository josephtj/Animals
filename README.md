


listView.setOnItemClickListener(new AdapterView.OnItemClickListener() {
            @Override
            public void onItemClick(AdapterView<?> parent, View view, int position, long id) {
                switch(position){
                    case 0:
                        Intent Bunny = new Intent(MainActivity.this,Bunny.class);
                        startActivity(Bunny);
                        break;
                    case 1:
                        Intent Cheetah = new Intent(MainActivity.this,Cheetah.class);
                        startActivity(Cheetah);
                        break;
                    case 2:
                        Intent Chicken = new Intent(MainActivity.this,Chicken.class);
                        startActivity(Chicken);
                }
            }
        });

